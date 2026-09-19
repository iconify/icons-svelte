<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-neh6-iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":436,"height":512};
const content = `<path class="s-neh6-iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:codemeta" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj5p2mlzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qj5p2mlzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:eagle" {...props}></Icon>

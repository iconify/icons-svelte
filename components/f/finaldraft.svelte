<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riduzfbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":331,"height":512};
const content = `<path class="riduzfbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:finaldraft" {...props}></Icon>

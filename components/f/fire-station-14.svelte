<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcroc_0yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rcroc_0yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:fire-station-14" {...props}></Icon>

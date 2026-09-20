<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szbfhrbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="szbfhrbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-waning-gibbous-3" {...props}></Icon>

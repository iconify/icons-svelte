<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_y7o7b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t_y7o7b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-mp4-filled" {...props}></Icon>

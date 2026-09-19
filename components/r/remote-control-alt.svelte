<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0ipyvbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":336,"height":456};
const content = `<path class="b0ipyvbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:remote-control-alt" {...props}></Icon>

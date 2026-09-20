<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-farr_vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m-farr_vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:jump-backwards-16" {...props}></Icon>

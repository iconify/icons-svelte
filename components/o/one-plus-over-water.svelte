<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg_i751ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xg_i751ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:one-plus-over-water" {...props}></Icon>

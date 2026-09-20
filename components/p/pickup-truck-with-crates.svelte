<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utvx-g6zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="utvx-g6zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickup-truck-with-crates" {...props}></Icon>

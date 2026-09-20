<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uissoqbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uissoqbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickup-truck-under-taxi-checkerboard" {...props}></Icon>

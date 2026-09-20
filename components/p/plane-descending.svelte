<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hss2rv_km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hss2rv_km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-descending" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-dmd_sjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="l-dmd_sjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:canoe" {...props}></Icon>

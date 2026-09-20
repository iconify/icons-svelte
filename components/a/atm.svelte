<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekdg5ur0t.css';
import '../../css/y/yor81gb5d.css';
import '../../css/u/u4_g3v0-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ekdg5ur0t"/><ellipse class="yor81gb5d"/><path class="u4_g3v0-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:atm" {...props}></Icon>

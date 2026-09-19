<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/r4f-rbb3p.css';
import '../../css/o/or62bbc5c.css';
import '../../css/u/ufz0b2bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="r4f-rbb3p"/><path class="or62bbc5c"/><path class="ufz0b2bzb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:caduceus" {...props}></Icon>

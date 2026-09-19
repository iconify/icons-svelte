<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wx_3q-bka.css';
import '../../css/k/kft13bcfg.css';
import '../../css/y/y8s0ycc7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="wx_3q-bka"/><path class="kft13bcfg"/><path class="y8s0ycc7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:house-damage-duo" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/m/mj9b5m6rh.css';
import '../../css/p/pjmjv_b-e.css';
import '../../css/v/vrai7hbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="mj9b5m6rh"/><path class="pjmjv_b-e"/><path class="vrai7hbra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:copy" {...props}></Icon>

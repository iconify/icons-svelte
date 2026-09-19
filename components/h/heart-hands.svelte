<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/p/ph05t8b0o.css';
import '../../css/a/a88zcbw0e.css';
import '../../css/p/pulgrgb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ph05t8b0o"/><path class="a88zcbw0e"/><path class="pulgrgb5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-hands" {...props}></Icon>

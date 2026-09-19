<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/k/ksso_xfmr.css';
import '../../css/q/qysl9rb8l.css';
import '../../css/b/bel2kzo2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ksso_xfmr"/><path class="qysl9rb8l"/><path class="bel2kzo2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:house-damage" {...props}></Icon>

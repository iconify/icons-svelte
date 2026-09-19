<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/u/ubyftdn1r.css';
import '../../css/f/fr7u0ubhf.css';
import '../../css/d/d6woa2e3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ubyftdn1r"/><path class="fr7u0ubhf"/><path class="d6woa2e3g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:house-flood" {...props}></Icon>

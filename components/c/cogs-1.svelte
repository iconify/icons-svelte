<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/k/kl9x8cb_k.css';
import '../../css/p/pj3sukt2m.css';
import '../../css/l/lu7yfhe2a.css';
import '../../css/m/mu5jj2lmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="kl9x8cb_k"/><path class="pj3sukt2m"/><path class="lu7yfhe2a"/><path class="mu5jj2lmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cogs-1" {...props}></Icon>

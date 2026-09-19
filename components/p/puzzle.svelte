<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/m/mj_tqmb9g.css';
import '../../css/l/loyg9l91u.css';
import '../../css/q/q85lzdbct.css';
import '../../css/d/dpj4gbi2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="mj_tqmb9g"/><path class="loyg9l91u"/><path class="q85lzdbct"/><path class="dpj4gbi2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:puzzle" {...props}></Icon>

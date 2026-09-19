<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/c/cvcvhiugj.css';
import '../../css/o/otj-prbjf.css';
import '../../css/k/k2hr7pzpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="cvcvhiugj"/><path class="otj-prbjf"/><path class="k2hr7pzpw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:coin" {...props}></Icon>

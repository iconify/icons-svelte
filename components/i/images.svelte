<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/t/tt9n7hbyj.css';
import '../../css/k/kwi6a8ecm.css';
import '../../css/x/x1c2z_baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="tt9n7hbyj"/><path class="kwi6a8ecm"/><path class="x1c2z_baq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:images" {...props}></Icon>

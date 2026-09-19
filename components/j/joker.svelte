<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/y/yom9-8bmz.css';
import '../../css/o/occmn0cmv.css';
import '../../css/n/nut2xvvam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="yom9-8bmz"/><path class="occmn0cmv"/><path class="nut2xvvam"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:joker" {...props}></Icon>

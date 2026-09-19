<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/n/n2wcz0b2s.css';
import '../../css/b/bjh1f82tm.css';
import '../../css/h/hx6xedbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="n2wcz0b2s"/><path class="bjh1f82tm"/><path class="hx6xedbpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:eye-1" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/u/u4tbqsblh.css';
import '../../css/i/ikozek9sr.css';
import '../../css/e/et_5w2bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="u4tbqsblh"/><path class="ikozek9sr"/><path class="et_5w2bcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:flip-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-ntwsbcy.css';
import '../../css/n/n8eg9qbgc.css';
import '../../css/p/p230cqbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f-ntwsbcy"/><path class="n8eg9qbgc"/><path class="p230cqbgr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:kiss-duo" {...props}></Icon>

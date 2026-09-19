<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yi0vp2biw.css';
import '../../css/p/plq8cklzl.css';
import '../../css/n/nqeg6l1lc.css';
import '../../css/n/ns361sykx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yi0vp2biw"/><path class="plq8cklzl"/><path clip-rule="evenodd" class="nqeg6l1lc"/><path class="ns361sykx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:brain-bold" {...props}></Icon>

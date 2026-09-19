<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x676eyzld.css';
import '../../css/i/i2h23ab7x.css';
import '../../css/v/vzoaje6mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="x676eyzld"/><path class="i2h23ab7x"/><path clip-rule="evenodd" class="vzoaje6mh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:images-1-bold" {...props}></Icon>

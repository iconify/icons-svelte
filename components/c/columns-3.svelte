<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopnm44um.css';
import '../../css/i/i9ptl6b7t.css';
import '../../css/t/txd1p9bsj.css';
import '../../css/u/uqgtd6bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="gopnm44um"><rect class="i9ptl6b7t"/><rect class="txd1p9bsj"/><rect class="uqgtd6bue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:columns-3" {...props}></Icon>

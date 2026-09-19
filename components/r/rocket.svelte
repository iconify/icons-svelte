<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z8c3n5wqq.css';
import '../../css/f/fyntx0zul.css';
import '../../css/y/ym8aceb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="z8c3n5wqq"/><path clip-rule="evenodd" class="fyntx0zul"/><path class="ym8aceb4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:rocket" {...props}></Icon>

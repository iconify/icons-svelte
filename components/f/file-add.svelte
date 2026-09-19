<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ueln8bb9d.css';
import '../../css/j/jvkbjcbed.css';
import '../../css/y/yg1c_-w4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ueln8bb9d"/><path class="jvkbjcbed"/><path class="yg1c_-w4j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:file-add" {...props}></Icon>

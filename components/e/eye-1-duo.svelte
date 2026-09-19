<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hnbhbrjgz.css';
import '../../css/s/sh6_yxm3e.css';
import '../../css/c/cu6ft-b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="hnbhbrjgz"/><path class="sh6_yxm3e"/><path class="cu6ft-b7q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:eye-1-duo" {...props}></Icon>

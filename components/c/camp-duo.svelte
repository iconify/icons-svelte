<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j07se6udc.css';
import '../../css/d/dr15u0bie.css';
import '../../css/v/vqlwd60yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="j07se6udc"/><path class="dr15u0bie"/><path class="vqlwd60yd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:camp-duo" {...props}></Icon>

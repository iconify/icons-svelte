<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n2g2lsb9m.css';
import '../../css/r/r8vx77qwt.css';
import '../../css/x/xduo7wb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="n2g2lsb9m"/><path class="r8vx77qwt"/><path class="xduo7wb9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-25-duo" {...props}></Icon>

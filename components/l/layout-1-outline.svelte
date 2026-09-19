<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qocopbb2u.css';
import '../../css/g/gi_h19bgs.css';
import '../../css/x/xpxc9t_-x.css';
import '../../css/u/ubcotg3vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="qocopbb2u"/><path clip-rule="evenodd" class="gi_h19bgs"/><path class="xpxc9t_-x"/><path clip-rule="evenodd" class="ubcotg3vs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:layout-1-outline" {...props}></Icon>

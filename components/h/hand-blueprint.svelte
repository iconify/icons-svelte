<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/j/jh5nocbzb.css';
import '../../css/g/g1p3n-bzh.css';
import '../../css/d/d2h7x8bev.css';
import '../../css/i/ibzfanbqt.css';
import '../../css/g/gmutfhb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="jh5nocbzb wm-deco"/><path class="g1p3n-bzh wm-deco"/><path class="d2h7x8bev wm-deco"/><path class="ibzfanbqt"/><path class="gmutfhb1q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hand-blueprint" {...props}></Icon>

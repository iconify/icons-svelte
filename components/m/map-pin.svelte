<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/x/xu1gn07mv.css';
import '../../css/r/rcd_5-bdr.css';
import '../../css/w/wogcsmb-x.css';
import '../../css/o/oe9845vhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="xu1gn07mv"/><path class="rcd_5-bdr"/><path class="wogcsmb-x"/><path class="oe9845vhp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:map-pin" {...props}></Icon>

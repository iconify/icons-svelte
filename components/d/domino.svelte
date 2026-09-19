<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gv48cybdb.css';
import '../../css/z/zx_m11buq.css';
import '../../css/s/ss02hqq4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gv48cybdb"/><path class="zx_m11buq"/><path class="ss02hqq4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:domino" {...props}></Icon>

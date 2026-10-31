<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/u/u1c40mbzp.css';
import '../../css/l/l-esgwk4n.css';
import '../../css/g/gfk1j8bwj.css';
import '../../css/x/xarwo-d3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="u1c40mbzp wm-shadow"/><path class="l-esgwk4n wm-shadow"/><path class="gfk1j8bwj"/><path class="xarwo-d3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:minimize" {...props}></Icon>

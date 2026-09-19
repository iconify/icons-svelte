<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xikknb5pn.css';
import '../../css/f/fp0qfxbzq.css';
import '../../css/o/ohu8q1bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xikknb5pn"/><path class="fp0qfxbzq"/><path class="ohu8q1bbk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:import" {...props}></Icon>

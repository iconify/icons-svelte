<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r7g2pcbpg.css';
import '../../css/g/gx1dibbnm.css';
import '../../css/u/ucj31ibdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r7g2pcbpg"/><path class="gx1dibbnm"/><path class="ucj31ibdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:power-filled" {...props}></Icon>

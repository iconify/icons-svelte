<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xk0sot7vu.css';
import '../../css/z/z0zxjzbsu.css';
import '../../css/l/laec6ibgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xk0sot7vu"/><path class="z0zxjzbsu"/><path class="laec6ibgw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:card-coin-filled" {...props}></Icon>

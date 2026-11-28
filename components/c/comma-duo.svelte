<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2af5cbuv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gw_btbw0f.css';
import '../../css/e/ec8kokbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary x2af5cbuv"/><g class="dt0cm9dhy primary"><path class="gw_btbw0f"/><path class="ec8kokbmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:comma-duo" {...props}></Icon>

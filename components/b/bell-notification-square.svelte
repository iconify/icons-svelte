<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/v/vj567d7up.css';
import '../../css/m/mcojq7b_o.css';
import '../../css/z/z7h9dmbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="vj567d7up"/><path class="mcojq7b_o"/><rect class="z7h9dmbpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:bell-notification-square" {...props}></Icon>

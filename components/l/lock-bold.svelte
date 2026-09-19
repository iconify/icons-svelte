<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/r/r99g0fbpd.css';
import '../../css/v/vynp5dscc.css';
import '../../css/t/t2u_xdb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="r99g0fbpd"/><path class="vynp5dscc"/><path class="t2u_xdb8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:lock-bold" {...props}></Icon>

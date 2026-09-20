<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/d/d_gtx6-4w.css';
import '../../css/n/nmdl3nrdn.css';
import '../../css/z/z7h9dmbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="d_gtx6-4w"/><path class="nmdl3nrdn"/><rect class="z7h9dmbpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:divide-square" {...props}></Icon>

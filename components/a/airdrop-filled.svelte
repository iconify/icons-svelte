<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/ldnjy29ps.css';
import '../../css/n/nv9013mnf.css';
import '../../css/k/ksnd1ac_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ldnjy29ps"/><path class="nv9013mnf"/><path class="ksnd1ac_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:airdrop-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls6_xn_4i.css';
import '../../css/x/x82v_8qul.css';
import '../../css/k/knxr7ab-k.css';
import '../../css/d/dxm8dzbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="ls6_xn_4i"><path class="x82v_8qul"/><circle class="knxr7ab-k"/><circle class="dxm8dzbyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:root" {...props}></Icon>

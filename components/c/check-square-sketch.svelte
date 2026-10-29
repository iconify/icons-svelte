<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pyd0g_0fv.css';
import '../../css/h/h_nrohbcx.css';
import '../../css/r/r7y8ybcsu.css';
import '../../css/v/v6xt2brxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pyd0g_0fv"/><path class="h_nrohbcx wm-a"/><path class="r7y8ybcsu wm-k"/><path class="v6xt2brxo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:check-square-sketch" {...props}></Icon>

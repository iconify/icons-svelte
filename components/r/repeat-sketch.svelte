<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kj_zj2cjc.css';
import '../../css/s/si9s5fb2e.css';
import '../../css/w/w4vj0mdzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kj_zj2cjc wm-k"/><path class="si9s5fb2e wm-k"/><path class="w4vj0mdzj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:repeat-sketch" {...props}></Icon>

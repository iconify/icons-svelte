<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k8xn_bcuz.css';
import '../../css/n/nu2pirbbg.css';
import '../../css/a/aftx_wyen.css';
import '../../css/q/qenlepbjq.css';
import '../../css/r/rd-9vfbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k8xn_bcuz"/><path class="nu2pirbbg wm-a"/><path class="aftx_wyen wm-k"/><path class="qenlepbjq wm-a"/><path class="rd-9vfbdz wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bell-dot-sketch" {...props}></Icon>

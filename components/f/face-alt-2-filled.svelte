<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qilianfni.css';
import '../../css/x/xdmtayb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qilianfni"/><path class="xdmtayb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:face-alt-2-filled" {...props}></Icon>

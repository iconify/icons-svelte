<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tun7kpbmr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tgy8uab8v.css';
import '../../css/t/tipdm0bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tun7kpbmr"/><g class="dt0cm9dhy primary"><path class="tgy8uab8v"/><path class="tipdm0bhg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-x-duo" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tgy8uab8v.css';
import '../../css/z/zyu_u8bwt.css';
import '../../css/n/nijo91b6q.css';
import '../../css/l/lbcpzmq3a.css';
import '../../css/e/e3qz36b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tgy8uab8v"/><path class="zyu_u8bwt"/><path class="nijo91b6q"/><path class="lbcpzmq3a"/><path class="e3qz36b2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-sync" {...props}></Icon>

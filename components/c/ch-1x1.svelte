<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/m/mjdv0zb8x.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/n/n-qrszsjk.css';
import '../../css/k/k76lkxb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="nv9qcacyl"><path class="mjdv0zb8x"/><g class="n1mjunbsu"><path class="n-qrszsjk"/><path class="k76lkxb4x"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ch-1x1" {...props}></Icon>

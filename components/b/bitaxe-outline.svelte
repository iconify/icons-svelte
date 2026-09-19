<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/b/bnqgp3bek.css';
import '../../css/t/t45dxeg-s.css';
import '../../css/m/mp0o2cb8i.css';
import '../../css/w/w7g_bfool.css';
import '../../css/c/cbje69b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="bnqgp3bek"/><path class="t45dxeg-s"/><path class="mp0o2cb8i"/><circle class="w7g_bfool"/><circle class="cbje69b4d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:bitaxe-outline" {...props}></Icon>

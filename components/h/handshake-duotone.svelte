<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zq9754muo.css';
import '../../css/f/f4_1a0dxw.css';
import '../../css/s/sh39dzt2r.css';
import '../../css/y/ybmaxr99i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zq9754muo"/><path class="f4_1a0dxw"/><path class="sh39dzt2r"/><path class="ybmaxr99i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:handshake-duotone" {...props}></Icon>

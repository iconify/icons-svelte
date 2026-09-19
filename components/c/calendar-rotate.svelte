<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/kuwd7bcos.css';
import '../../css/o/on2pvo0gv.css';
import '../../css/l/lx_zx5b2t.css';
import '../../css/p/pk5i1dr7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kuwd7bcos"/><path class="on2pvo0gv"/><path class="lx_zx5b2t"/><path class="pk5i1dr7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:calendar-rotate" {...props}></Icon>

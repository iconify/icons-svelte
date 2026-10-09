<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_xg23xbo.css';
import '../../css/y/y5ccdmbcq.css';
import '../../css/p/p1e2i1bne.css';
import '../../css/q/qpsxe7qzz.css';
import '../../css/u/u8qqsxbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c_xg23xbo"/><path class="y5ccdmbcq"/><path class="p1e2i1bne"/><path class="qpsxe7qzz"/><path class="u8qqsxbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-flow-20-bold" {...props}></Icon>

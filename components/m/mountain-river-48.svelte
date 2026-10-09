<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx5i_8glh.css';
import '../../css/u/uyhqdeb9l.css';
import '../../css/u/ua2_qkbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sx5i_8glh"/><path class="uyhqdeb9l"/><path class="ua2_qkbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mountain-river-48" {...props}></Icon>

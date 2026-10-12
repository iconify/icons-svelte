<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrvv8ub0p.css';
import '../../css/w/w0l__2bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zrvv8ub0p"/><path class="w0l__2bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:camera-stroke-20" {...props}></Icon>

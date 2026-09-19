<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrbpuobsp.css';
import '../../css/a/a_k2ufbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mrbpuobsp"/><path class="a_k2ufbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:circle-down" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prt_k_bso.css';
import '../../css/k/koi711brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="prt_k_bso"/><path class="koi711brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mushroom-20" {...props}></Icon>

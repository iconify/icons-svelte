<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lezm_k3dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lezm_k3dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-down-20" {...props}></Icon>

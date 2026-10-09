<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tydcr7btg.css';
import '../../css/k/krbzztkfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tydcr7btg"/><path class="krbzztkfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:award-20-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o97q_2bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o97q_2bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:chart-pie" {...props}></Icon>

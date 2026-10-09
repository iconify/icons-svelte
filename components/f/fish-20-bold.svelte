<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owtzhwipg.css';
import '../../css/s/sj9o9bcjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="owtzhwipg"/><path class="sj9o9bcjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fish-20-bold" {...props}></Icon>

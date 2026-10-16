<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy0q0mjxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gy0q0mjxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:insurance-20-bold" {...props}></Icon>

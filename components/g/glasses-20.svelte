<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tub7k1bln.css';
import '../../css/q/q3_36q7xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tub7k1bln"/><path class="q3_36q7xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:glasses-20" {...props}></Icon>

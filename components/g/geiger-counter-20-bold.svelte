<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siqjgac7n.css';
import '../../css/m/mplihkbyd.css';
import '../../css/h/hplakgb5n.css';
import '../../css/o/oh4_jp9dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="siqjgac7n"/><path class="mplihkbyd"/><path class="hplakgb5n"/><path class="oh4_jp9dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:geiger-counter-20-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxz4cubom.css';
import '../../css/i/iv8yz13mj.css';
import '../../css/l/lv8uq9bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mxz4cubom"/><path class="iv8yz13mj"/><path class="lv8uq9bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chicken-leg-20-bold" {...props}></Icon>

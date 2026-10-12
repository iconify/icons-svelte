<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwxtv1bud.css';
import '../../css/y/y3799mbrd.css';
import '../../css/w/wix60v6xk.css';
import '../../css/w/w-bdeccnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dwxtv1bud"/><path class="y3799mbrd"/><path class="wix60v6xk"/><path class="w-bdeccnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pressure-gauge-20" {...props}></Icon>

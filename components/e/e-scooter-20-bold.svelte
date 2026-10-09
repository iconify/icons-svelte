<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m67zmkbra.css';
import '../../css/v/v2pxd9boo.css';
import '../../css/q/qj3hxybqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m67zmkbra"/><path class="v2pxd9boo"/><path class="qj3hxybqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:e-scooter-20-bold" {...props}></Icon>

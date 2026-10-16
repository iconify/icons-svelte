<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6jy34m0o.css';
import '../../css/y/yop_hibwm.css';
import '../../css/h/hhhkbob2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y6jy34m0o"/><path class="yop_hibwm"/><path class="hhhkbob2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-optimiser-20-bold" {...props}></Icon>

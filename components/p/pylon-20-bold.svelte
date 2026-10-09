<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn92pkbuc.css';
import '../../css/m/myl9aibrd.css';
import '../../css/e/etzqvpx1q.css';
import '../../css/n/nt1j3jajj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bn92pkbuc"/><path class="myl9aibrd"/><path class="etzqvpx1q"/><path class="nt1j3jajj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pylon-20-bold" {...props}></Icon>

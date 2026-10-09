<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krobukb5c.css';
import '../../css/t/tbhx0yb6y.css';
import '../../css/m/m3r1373vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="krobukb5c"/><path class="tbhx0yb6y"/><path class="m3r1373vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paint-roller-20" {...props}></Icon>

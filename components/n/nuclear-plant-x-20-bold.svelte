<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey18pvvad.css';
import '../../css/c/cbw0uj2ck.css';
import '../../css/l/l3qindbue.css';
import '../../css/f/fdtytm4ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ey18pvvad"/><path class="cbw0uj2ck"/><path class="l3qindbue"/><path class="fdtytm4ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nuclear-plant-x-20-bold" {...props}></Icon>

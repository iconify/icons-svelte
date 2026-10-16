<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4z_7vrmz.css';
import '../../css/t/t_ln7kttq.css';
import '../../css/o/owb9_xn9q.css';
import '../../css/h/hpjl1xeux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a4z_7vrmz"/><path class="t_ln7kttq"/><path class="owb9_xn9q"/><path class="hpjl1xeux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:airborne-wind-20-bold" {...props}></Icon>

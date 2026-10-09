<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyt2h3uvs.css';
import '../../css/z/zb43x5bxp.css';
import '../../css/m/mp27osukt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hyt2h3uvs"/><path class="zb43x5bxp"/><path class="mp27osukt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hotel-20-bold" {...props}></Icon>

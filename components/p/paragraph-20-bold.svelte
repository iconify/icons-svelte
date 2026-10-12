<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpg9p2bhv.css';
import '../../css/l/l05mycboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hpg9p2bhv"/><path class="l05mycboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paragraph-20-bold" {...props}></Icon>

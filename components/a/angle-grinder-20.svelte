<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao-tyjbir.css';
import '../../css/r/rtr7zsbdu.css';
import '../../css/d/don67qb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ao-tyjbir"/><path class="rtr7zsbdu"/><path class="don67qb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:angle-grinder-20" {...props}></Icon>

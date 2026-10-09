<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snm0mpkao.css';
import '../../css/r/rm_syy1jr.css';
import '../../css/r/rwupt7b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="snm0mpkao"/><path class="rm_syy1jr"/><path class="rwupt7b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:castle-20-bold" {...props}></Icon>

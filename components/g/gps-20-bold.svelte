<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb96ptbmh.css';
import '../../css/n/n_yelj1ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tb96ptbmh"/><path class="n_yelj1ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gps-20-bold" {...props}></Icon>

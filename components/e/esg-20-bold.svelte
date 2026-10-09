<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdw3vx8xp.css';
import '../../css/j/j-4k2f7vu.css';
import '../../css/w/w3544mb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fdw3vx8xp"/><path class="j-4k2f7vu"/><path class="w3544mb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:esg-20-bold" {...props}></Icon>

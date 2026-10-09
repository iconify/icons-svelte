<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w07o7rb0l.css';
import '../../css/z/z4o_8eb_q.css';
import '../../css/y/yvyc8v67g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w07o7rb0l"/><path class="z4o_8eb_q"/><path class="yvyc8v67g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:archery-20-bold" {...props}></Icon>

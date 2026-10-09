<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q97zhzb7g.css';
import '../../css/v/v361qqj9p.css';
import '../../css/u/ufgiultbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q97zhzb7g"/><path class="v361qqj9p"/><path class="ufgiultbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:goal-20-bold" {...props}></Icon>

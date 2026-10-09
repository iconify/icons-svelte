<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmgp-hp4m.css';
import '../../css/p/pp2z-qb2n.css';
import '../../css/d/dp7t9qbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rmgp-hp4m"/><path class="pp2z-qb2n"/><path class="dp7t9qbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:retrofit-20-bold" {...props}></Icon>

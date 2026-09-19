<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iql1lvbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iql1lvbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pathfinder-unite" {...props}></Icon>

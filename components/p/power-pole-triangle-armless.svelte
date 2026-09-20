<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n836y-tcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n836y-tcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-pole-triangle-armless" {...props}></Icon>

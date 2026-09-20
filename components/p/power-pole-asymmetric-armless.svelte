<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-dyeon3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q-dyeon3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-pole-asymmetric-armless" {...props}></Icon>

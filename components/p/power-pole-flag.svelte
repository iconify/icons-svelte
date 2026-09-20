<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6xmncb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s6xmncb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-pole-flag" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw_2ghb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fw_2ghb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-pole-3-level" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i46bncbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i46bncbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-tower-delta-3-level" {...props}></Icon>

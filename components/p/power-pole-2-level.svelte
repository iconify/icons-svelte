<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paa32pj0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="paa32pj0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-pole-2-level" {...props}></Icon>

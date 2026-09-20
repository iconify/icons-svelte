<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa-r_c5vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wa-r_c5vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nested" {...props}></Icon>

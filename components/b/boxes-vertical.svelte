<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa-00nb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wa-00nb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:boxes-vertical" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id3fg2b_m.css';
import '../../css/u/u59sblbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="id3fg2b_m"/><path class="u59sblbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biofuel-20" {...props}></Icon>

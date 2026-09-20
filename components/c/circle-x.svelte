<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa34macfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wa34macfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:circle-x" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke6-nwbts.css';
import '../../css/o/od4sw7bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ke6-nwbts"/><path class="od4sw7bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:currency-shekel" {...props}></Icon>

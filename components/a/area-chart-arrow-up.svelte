<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdwak9bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdwak9bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:area-chart-arrow-up" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2qeb8bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v2qeb8bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-2-story-skillion-roof" {...props}></Icon>

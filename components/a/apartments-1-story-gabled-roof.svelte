<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvb49db5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rvb49db5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-1-story-gabled-roof" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr6emiboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rr6emiboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-4-story-skillion-roof" {...props}></Icon>

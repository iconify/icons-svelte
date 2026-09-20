<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_-_5ac1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h_-_5ac1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-5-story-gabled-roof" {...props}></Icon>

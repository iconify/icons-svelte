<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3qpvprfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y3qpvprfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-2-story-gabled-roof" {...props}></Icon>

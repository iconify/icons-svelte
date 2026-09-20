<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p678uh31n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p678uh31n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-3-story-gabled-roof" {...props}></Icon>

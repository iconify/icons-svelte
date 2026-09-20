<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcnm0i4-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jcnm0i4-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bench-with-shelter" {...props}></Icon>

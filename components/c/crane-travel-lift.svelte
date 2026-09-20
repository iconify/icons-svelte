<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9d6omb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d9d6omb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:crane-travel-lift" {...props}></Icon>

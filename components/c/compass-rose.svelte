<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3iqqrbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p3iqqrbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:compass-rose" {...props}></Icon>

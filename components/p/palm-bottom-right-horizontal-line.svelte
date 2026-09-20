<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtsxvz0cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rtsxvz0cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:palm-bottom-right-horizontal-line" {...props}></Icon>

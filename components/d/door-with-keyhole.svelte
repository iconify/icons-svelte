<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9f9t-wdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p9f9t-wdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:door-with-keyhole" {...props}></Icon>

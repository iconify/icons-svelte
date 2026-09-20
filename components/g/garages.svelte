<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a99lazb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a99lazb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:garages" {...props}></Icon>

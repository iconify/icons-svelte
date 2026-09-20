<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpfjh6p0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gpfjh6p0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:fire-hydrant" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8zqmhn6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l8zqmhn6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:broadcast" {...props}></Icon>

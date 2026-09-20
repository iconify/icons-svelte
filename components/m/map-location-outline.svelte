<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7qn6rb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u7qn6rb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:map-location-outline" {...props}></Icon>

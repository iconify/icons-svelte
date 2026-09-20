<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r69wl1bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="r69wl1bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:pause" {...props}></Icon>

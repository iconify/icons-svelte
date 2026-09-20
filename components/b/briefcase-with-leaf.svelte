<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1ssddo4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v1ssddo4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-leaf" {...props}></Icon>

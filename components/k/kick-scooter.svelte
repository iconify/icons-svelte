<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw-4-8pcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iw-4-8pcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:kick-scooter" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f56jpdb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="f56jpdb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:dry" {...props}></Icon>

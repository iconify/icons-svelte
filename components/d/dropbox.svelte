<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6rrxu8ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":400};
const content = `<path class="a6rrxu8ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:dropbox" {...props}></Icon>

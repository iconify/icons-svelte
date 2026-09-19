<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqcm5iqdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqcm5iqdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:clone" {...props}></Icon>

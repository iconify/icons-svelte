<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg3t_8bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cg3t_8bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:notification-stroke-12" {...props}></Icon>

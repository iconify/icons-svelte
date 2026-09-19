<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uav6kirzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uav6kirzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:notification-stroke-16" {...props}></Icon>

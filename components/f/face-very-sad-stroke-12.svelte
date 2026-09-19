<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt87vo4px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dt87vo4px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:face-very-sad-stroke-12" {...props}></Icon>

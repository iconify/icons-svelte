<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn6mf84ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zn6mf84ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pin-stroke-12" {...props}></Icon>

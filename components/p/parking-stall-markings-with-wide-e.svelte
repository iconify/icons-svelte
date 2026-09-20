<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri-3uvbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ri-3uvbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:parking-stall-markings-with-wide-e" {...props}></Icon>

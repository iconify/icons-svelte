<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzp5z8b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pzp5z8b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:glass" {...props}></Icon>

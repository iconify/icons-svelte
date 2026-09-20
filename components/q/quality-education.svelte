<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfwp-acbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rfwp-acbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:quality-education" {...props}></Icon>

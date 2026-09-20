<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvuqs7byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gvuqs7byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:box" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkvud5qcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lkvud5qcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:crates-in-rectangle-under-arrow-up-beside-arrow-down" {...props}></Icon>

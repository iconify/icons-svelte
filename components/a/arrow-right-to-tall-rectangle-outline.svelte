<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi2gxlb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zi2gxlb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-right-to-tall-rectangle-outline" {...props}></Icon>

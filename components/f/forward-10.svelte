<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olgjpxlkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="olgjpxlkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:forward-10" {...props}></Icon>

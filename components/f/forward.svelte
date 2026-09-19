<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llc80zbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="llc80zbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:forward" {...props}></Icon>

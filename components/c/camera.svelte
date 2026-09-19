<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6uo6chtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":472};
const content = `<path class="r6uo6chtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:camera" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8mqu0b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w8mqu0b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:add-1" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7ka-c69h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n7ka-c69h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ring-with-jewel" {...props}></Icon>

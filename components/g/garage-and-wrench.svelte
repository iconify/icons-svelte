<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um98v6b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="um98v6b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:garage-and-wrench" {...props}></Icon>

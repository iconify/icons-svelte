<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8zb9sb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="z8zb9sb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:battery-empty" {...props}></Icon>

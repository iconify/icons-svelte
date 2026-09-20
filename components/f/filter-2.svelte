<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgsi59b4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bgsi59b4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:filter-2" {...props}></Icon>

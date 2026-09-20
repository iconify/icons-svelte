<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc1ttrbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="dc1ttrbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:google-drive" {...props}></Icon>

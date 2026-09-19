<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd8x7abdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="xd8x7abdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:reddit" {...props}></Icon>

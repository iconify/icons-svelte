<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjah9mb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="pjah9mb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:filter" {...props}></Icon>

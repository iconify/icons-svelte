<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_8fwfbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="b_8fwfbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:css" {...props}></Icon>

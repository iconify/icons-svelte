<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad5uotbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="ad5uotbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:expeditedssl" {...props}></Icon>

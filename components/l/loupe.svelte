<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7grmv2fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="a7grmv2fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:loupe" {...props}></Icon>

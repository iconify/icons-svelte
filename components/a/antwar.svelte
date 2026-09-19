<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy6eb_buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gy6eb_buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:antwar" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc910e6zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xc910e6zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-folder-empty-folder" {...props}></Icon>

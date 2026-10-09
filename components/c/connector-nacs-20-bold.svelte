<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vea99ibyc.css';
import '../../css/y/ybtvnxb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vea99ibyc"/><path class="ybtvnxb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-nacs-20-bold" {...props}></Icon>

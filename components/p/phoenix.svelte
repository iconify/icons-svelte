<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gag2-lbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gag2-lbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:phoenix" {...props}></Icon>

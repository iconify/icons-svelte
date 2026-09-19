<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yilqdacnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":432};
const content = `<path class="yilqdacnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:notifications-active" {...props}></Icon>

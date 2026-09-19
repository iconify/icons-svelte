<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn5c3hbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="vn5c3hbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:block" {...props}></Icon>

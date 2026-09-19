<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9azydbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":480};
const content = `<path class="n9azydbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:network-off" {...props}></Icon>

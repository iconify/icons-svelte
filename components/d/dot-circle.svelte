<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk70cdcpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="wk70cdcpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:dot-circle" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioxi_abwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ioxi_abwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-diving" {...props}></Icon>

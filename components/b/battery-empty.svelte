<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju2p32bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="ju2p32bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:battery-empty" {...props}></Icon>

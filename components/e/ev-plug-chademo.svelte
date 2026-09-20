<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a65ywmupk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a65ywmupk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ev-plug-chademo" {...props}></Icon>

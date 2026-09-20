<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbbtivbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbbtivbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cpu-32-bit" {...props}></Icon>

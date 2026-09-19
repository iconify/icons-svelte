<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybx8r3b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybx8r3b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:logs" {...props}></Icon>

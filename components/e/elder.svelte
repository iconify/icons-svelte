<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn0e0ac1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn0e0ac1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:elder" {...props}></Icon>

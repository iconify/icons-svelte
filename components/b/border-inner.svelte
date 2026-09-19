<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xybm8_bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xybm8_bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:border-inner" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2c-s1u4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2c-s1u4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:candlestick" {...props}></Icon>

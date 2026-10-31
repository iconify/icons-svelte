<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7mm91p0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7mm91p0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:map-pin-fill-round" {...props}></Icon>

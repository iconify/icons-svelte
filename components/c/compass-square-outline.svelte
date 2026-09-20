<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trt_o2bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="trt_o2bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:compass-square-outline" {...props}></Icon>

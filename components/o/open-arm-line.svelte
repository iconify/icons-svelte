<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlrq2rbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlrq2rbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:open-arm-line" {...props}></Icon>

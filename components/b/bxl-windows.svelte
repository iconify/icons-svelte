<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7hv-mbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7hv-mbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-windows" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvgx_ibgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvgx_ibgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:direction-arrow-line" {...props}></Icon>

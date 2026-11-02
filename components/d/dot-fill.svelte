<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khz5z_bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khz5z_bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dot-fill" {...props}></Icon>

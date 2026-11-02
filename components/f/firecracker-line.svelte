<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg_d3jumz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg_d3jumz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:firecracker-line" {...props}></Icon>

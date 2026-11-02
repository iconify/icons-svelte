<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yao8nb-za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yao8nb-za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-no-axes-combined-fill" {...props}></Icon>

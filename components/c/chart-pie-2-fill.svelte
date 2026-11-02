<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izwoc4b1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izwoc4b1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-pie-2-fill" {...props}></Icon>

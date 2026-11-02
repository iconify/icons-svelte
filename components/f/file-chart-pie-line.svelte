<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8vovltvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8vovltvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-chart-pie-line" {...props}></Icon>

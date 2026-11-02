<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u74c4ybvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u74c4ybvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-chart-pie-fill" {...props}></Icon>

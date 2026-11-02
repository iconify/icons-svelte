<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbs7r8msg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbs7r8msg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-chart-column-increasing-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qikfyukbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qikfyukbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-no-axes-column-decreasing-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4w_1w7kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4w_1w7kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fan-line" {...props}></Icon>

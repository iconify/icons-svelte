<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-4l5nx5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m-4l5nx5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:candle-fill" {...props}></Icon>

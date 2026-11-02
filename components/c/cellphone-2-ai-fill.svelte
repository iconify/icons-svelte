<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4rkire3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4rkire3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cellphone-2-ai-fill" {...props}></Icon>

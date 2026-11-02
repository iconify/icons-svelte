<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulnrl9bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulnrl9bri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:history-anticlockwise-fill" {...props}></Icon>

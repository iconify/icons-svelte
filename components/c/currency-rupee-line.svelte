<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5o9ygl0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5o9ygl0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-rupee-line" {...props}></Icon>

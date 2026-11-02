<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xayzjabqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xayzjabqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-ruble-line" {...props}></Icon>

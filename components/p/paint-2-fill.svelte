<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuiu9qgrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuiu9qgrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paint-2-fill" {...props}></Icon>

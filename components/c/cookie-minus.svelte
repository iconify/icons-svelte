<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiix6ccxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiix6ccxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cookie-minus" {...props}></Icon>

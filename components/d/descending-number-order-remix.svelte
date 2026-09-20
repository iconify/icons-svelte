<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-09s6buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i-09s6buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:descending-number-order-remix" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgz8urb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zgz8urb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:minus-ten-circle" {...props}></Icon>

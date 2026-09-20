<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5dw-kbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p5dw-kbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:cellular-network-lte" {...props}></Icon>

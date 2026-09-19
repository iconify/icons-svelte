<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9aio8bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9aio8bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-pictures" {...props}></Icon>

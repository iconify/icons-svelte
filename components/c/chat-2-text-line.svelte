<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jecgmcqwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jecgmcqwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chat-2-text-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-g5z-w8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-g5z-w8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-alt-edit" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8-1o0_1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8-1o0_1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cannabis" {...props}></Icon>

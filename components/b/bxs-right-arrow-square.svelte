<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0xxe-6gb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0xxe-6gb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-right-arrow-square" {...props}></Icon>

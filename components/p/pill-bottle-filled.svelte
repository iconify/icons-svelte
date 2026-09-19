<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr54h2ycg.css';
import '../../css/e/e4rr4w_hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="zr54h2ycg"/><path class="e4rr4w_hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pill-bottle-filled" {...props}></Icon>

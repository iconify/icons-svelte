<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgi9bnbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgi9bnbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-box" {...props}></Icon>

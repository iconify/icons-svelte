<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdp5dhbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdp5dhbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-wix" {...props}></Icon>

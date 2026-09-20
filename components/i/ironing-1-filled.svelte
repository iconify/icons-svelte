<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zro8_s1yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zro8_s1yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ironing-1-filled" {...props}></Icon>

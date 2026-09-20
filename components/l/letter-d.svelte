<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpu8nbc8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpu8nbc8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-d" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlsefonkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlsefonkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:corner-down-right" {...props}></Icon>

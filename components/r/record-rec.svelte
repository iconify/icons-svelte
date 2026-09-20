<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx8l00b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx8l00b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:record-rec" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp9g6ccaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp9g6ccaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:adobe" {...props}></Icon>

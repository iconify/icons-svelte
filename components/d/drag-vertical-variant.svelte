<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvgox7b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvgox7b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:drag-vertical-variant" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsl8l22wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsl8l22wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mustache" {...props}></Icon>

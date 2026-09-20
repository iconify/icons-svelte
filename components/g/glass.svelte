<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl5m1kbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl5m1kbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:glass" {...props}></Icon>

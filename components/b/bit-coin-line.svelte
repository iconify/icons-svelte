<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-sqk0b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-sqk0b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bit-coin-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oczlvwbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oczlvwbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-plus-fill" {...props}></Icon>

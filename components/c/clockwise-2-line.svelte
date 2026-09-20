<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4hl1y05t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4hl1y05t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:clockwise-2-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpd_f5y1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpd_f5y1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:focus-3-line" {...props}></Icon>

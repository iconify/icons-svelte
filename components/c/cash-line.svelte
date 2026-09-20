<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpixu049r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpixu049r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cash-line" {...props}></Icon>

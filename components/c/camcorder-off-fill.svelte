<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_l5p3i7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_l5p3i7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-off-fill" {...props}></Icon>

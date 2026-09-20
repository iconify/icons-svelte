<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx2k6dbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx2k6dbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chart-areaspline-variant" {...props}></Icon>

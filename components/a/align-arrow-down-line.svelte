<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veevc8lbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veevc8lbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-arrow-down-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cet4g5u_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cet4g5u_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:milkshake" {...props}></Icon>

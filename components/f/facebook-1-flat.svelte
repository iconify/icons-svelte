<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxz7qzbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="uxz7qzbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:facebook-1-flat" {...props}></Icon>

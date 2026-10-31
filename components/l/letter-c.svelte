<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi2x7ybxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi2x7ybxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-c" {...props}></Icon>

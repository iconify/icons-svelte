<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cspskybef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cspskybef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:prohibited-line" {...props}></Icon>

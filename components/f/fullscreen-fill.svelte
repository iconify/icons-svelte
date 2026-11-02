<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6_fa-bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6_fa-bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fullscreen-fill" {...props}></Icon>

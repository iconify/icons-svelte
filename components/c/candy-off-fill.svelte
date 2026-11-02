<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p08m16bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p08m16bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:candy-off-fill" {...props}></Icon>

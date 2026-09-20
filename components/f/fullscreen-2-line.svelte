<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2bf_gb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2bf_gb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fullscreen-2-line" {...props}></Icon>

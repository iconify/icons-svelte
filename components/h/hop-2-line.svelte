<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwue91e1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwue91e1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hop-2-line" {...props}></Icon>

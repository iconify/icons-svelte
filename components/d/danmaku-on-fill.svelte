<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/ximv8ihgl.css';
import '../../css/p/pl259k1fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ximv8ihgl"/><path class="pl259k1fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:danmaku-on-fill" {...props}></Icon>

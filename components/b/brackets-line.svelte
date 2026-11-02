<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhxsndbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhxsndbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brackets-line" {...props}></Icon>

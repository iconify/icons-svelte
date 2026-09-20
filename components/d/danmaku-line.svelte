<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggrv6-bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggrv6-bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:danmaku-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewv6nub2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewv6nub2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-outer-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j47thmb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j47thmb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airdrop-line" {...props}></Icon>

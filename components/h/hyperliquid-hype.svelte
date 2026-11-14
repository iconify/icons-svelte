<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z044ykbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z044ykbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hyperliquid-hype" {...props}></Icon>

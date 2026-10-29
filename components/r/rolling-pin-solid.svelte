<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcaniacwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcaniacwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rolling-pin-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk0n2ybxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk0n2ybxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-cog" {...props}></Icon>

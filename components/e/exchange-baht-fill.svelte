<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhfphl-pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhfphl-pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-baht-fill" {...props}></Icon>

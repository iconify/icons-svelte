<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdsz5c2ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdsz5c2ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:business-deal-cash-2" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0i3rcc6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0i3rcc6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bank-transfer-out" {...props}></Icon>

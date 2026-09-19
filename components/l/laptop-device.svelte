<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr-6bxncg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr-6bxncg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:laptop-device" {...props}></Icon>

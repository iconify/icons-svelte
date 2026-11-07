<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swf6libns.css';
import '../../css/n/nosnhobdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swf6libns"/><path class="nosnhobdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-smile-angle-bold-duotone" {...props}></Icon>

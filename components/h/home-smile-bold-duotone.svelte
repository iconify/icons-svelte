<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jglmwo91y.css';
import '../../css/x/x0rle6bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jglmwo91y"/><path class="x0rle6bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-smile-bold-duotone" {...props}></Icon>

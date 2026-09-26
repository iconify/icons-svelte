<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt2-4yxgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt2-4yxgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-vertical-linear" {...props}></Icon>

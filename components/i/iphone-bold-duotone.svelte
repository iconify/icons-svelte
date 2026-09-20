<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyz0sxbtx.css';
import '../../css/g/g773-itfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyz0sxbtx"/><path class="g773-itfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:iphone-bold-duotone" {...props}></Icon>

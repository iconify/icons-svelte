<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t737ombpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t737ombpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:battery-full" {...props}></Icon>

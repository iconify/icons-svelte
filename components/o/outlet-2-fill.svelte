<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr_-pwids.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr_-pwids"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:outlet-2-fill" {...props}></Icon>

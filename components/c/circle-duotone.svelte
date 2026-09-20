<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkbv002zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkbv002zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-duotone" {...props}></Icon>

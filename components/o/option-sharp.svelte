<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy_b46cyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy_b46cyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:option-sharp" {...props}></Icon>

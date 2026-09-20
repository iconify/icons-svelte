<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn728lqcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn728lqcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:men-line" {...props}></Icon>

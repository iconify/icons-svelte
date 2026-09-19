<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yem4isb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yem4isb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-top-left" {...props}></Icon>

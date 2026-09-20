<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6x0_ubyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6x0_ubyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:code-s-fill" {...props}></Icon>

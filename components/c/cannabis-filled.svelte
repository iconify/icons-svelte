<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl0va5bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl0va5bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cannabis-filled" {...props}></Icon>

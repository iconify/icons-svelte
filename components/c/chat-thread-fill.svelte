<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf2c8xxts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf2c8xxts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-thread-fill" {...props}></Icon>

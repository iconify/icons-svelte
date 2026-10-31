<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db68k-bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db68k-bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bell-ring-round" {...props}></Icon>

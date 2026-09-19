<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0xf25b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0xf25b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:menu-09" {...props}></Icon>

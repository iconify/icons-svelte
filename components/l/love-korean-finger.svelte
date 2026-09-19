<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-x6y2uyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-x6y2uyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:love-korean-finger" {...props}></Icon>

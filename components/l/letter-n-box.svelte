<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz2t82xpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz2t82xpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-n-box" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwizefb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wwizefb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cooking-glove" {...props}></Icon>

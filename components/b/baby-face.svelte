<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kei78h1bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kei78h1bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:baby-face" {...props}></Icon>

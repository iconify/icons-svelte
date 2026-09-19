<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yss1rp-_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yss1rp-_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:oasis" {...props}></Icon>

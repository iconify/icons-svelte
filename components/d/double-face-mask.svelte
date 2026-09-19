<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auj86-bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="auj86-bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:double-face-mask" {...props}></Icon>

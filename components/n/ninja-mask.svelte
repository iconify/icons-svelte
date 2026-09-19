<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b56svt4rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b56svt4rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ninja-mask" {...props}></Icon>

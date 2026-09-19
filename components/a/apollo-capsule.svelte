<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj3psbbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tj3psbbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:apollo-capsule" {...props}></Icon>

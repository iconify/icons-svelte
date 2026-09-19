<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaeag1s_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qaeag1s_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:full-pizza" {...props}></Icon>

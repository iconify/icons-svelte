<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_-10o11k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k_-10o11k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ceremonial-mask" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmx42-grk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kmx42-grk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heaven-gate" {...props}></Icon>

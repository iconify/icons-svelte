<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfmm-1b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kfmm-1b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chips-bag" {...props}></Icon>

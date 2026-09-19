<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri7kwcc0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ri7kwcc0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:missile-pod" {...props}></Icon>

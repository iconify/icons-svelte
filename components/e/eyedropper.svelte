<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm-gy2bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lm-gy2bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:eyedropper" {...props}></Icon>

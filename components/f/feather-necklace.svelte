<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_9f3ie_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_9f3ie_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:feather-necklace" {...props}></Icon>

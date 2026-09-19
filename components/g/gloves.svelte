<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtfey4brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wtfey4brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gloves" {...props}></Icon>

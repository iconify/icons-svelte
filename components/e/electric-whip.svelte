<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3karoc9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z3karoc9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:electric-whip" {...props}></Icon>

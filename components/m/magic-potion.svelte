<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl88qba3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cl88qba3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magic-potion" {...props}></Icon>

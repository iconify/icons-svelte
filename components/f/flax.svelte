<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhspo-6xc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uhspo-6xc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flax" {...props}></Icon>

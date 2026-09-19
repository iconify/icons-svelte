<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt0wzmbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mt0wzmbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:open-palm" {...props}></Icon>

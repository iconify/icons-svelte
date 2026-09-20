<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7d7i_big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k7d7i_big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:backpack-remix" {...props}></Icon>

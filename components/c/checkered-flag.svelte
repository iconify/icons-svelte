<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxtm2khtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pxtm2khtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:checkered-flag" {...props}></Icon>

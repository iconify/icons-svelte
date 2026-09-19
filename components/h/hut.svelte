<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whl4o-bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="whl4o-bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hut" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czgzvkbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="czgzvkbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:beard" {...props}></Icon>

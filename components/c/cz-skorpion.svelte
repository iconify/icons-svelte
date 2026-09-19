<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twnv2zbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="twnv2zbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cz-skorpion" {...props}></Icon>

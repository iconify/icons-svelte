<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teo0ohb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="teo0ohb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:riposte" {...props}></Icon>

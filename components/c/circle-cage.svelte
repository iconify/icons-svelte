<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thwo9b10l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="thwo9b10l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:circle-cage" {...props}></Icon>

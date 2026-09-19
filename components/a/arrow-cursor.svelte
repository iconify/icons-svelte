<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzht7_bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zzht7_bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:arrow-cursor" {...props}></Icon>

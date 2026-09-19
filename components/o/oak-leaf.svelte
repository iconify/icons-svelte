<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6ypdacha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z6ypdacha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:oak-leaf" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3u9lnadn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j3u9lnadn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dripping-stone" {...props}></Icon>

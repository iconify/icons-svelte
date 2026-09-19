<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxquwkbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jxquwkbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:leather-boot" {...props}></Icon>

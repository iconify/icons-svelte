<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2hm0dbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n2hm0dbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:klingon" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnjdtwsnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gnjdtwsnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:banana-peeled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayd73xbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ayd73xbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bubbles" {...props}></Icon>

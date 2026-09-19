<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtsz6d8hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jtsz6d8hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-5-spades" {...props}></Icon>

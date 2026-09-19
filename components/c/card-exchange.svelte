<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waqu08mrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="waqu08mrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-exchange" {...props}></Icon>

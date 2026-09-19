<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbh6wac8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zbh6wac8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:harbor-dock" {...props}></Icon>

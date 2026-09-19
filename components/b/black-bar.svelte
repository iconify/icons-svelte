<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_vs-hd3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_vs-hd3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:black-bar" {...props}></Icon>

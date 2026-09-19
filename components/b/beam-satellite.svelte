<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4ax9-_0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q4ax9-_0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:beam-satellite" {...props}></Icon>

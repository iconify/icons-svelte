<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1y_t1x2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s1y_t1x2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:calculator" {...props}></Icon>

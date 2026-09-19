<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q53r2u7fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q53r2u7fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:liar" {...props}></Icon>

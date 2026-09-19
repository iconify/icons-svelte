<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcg36hbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bcg36hbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heavy-timer" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/setq1eb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="setq1eb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heavy-bullets" {...props}></Icon>

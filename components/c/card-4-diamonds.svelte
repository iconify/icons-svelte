<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9iptvk5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g9iptvk5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-4-diamonds" {...props}></Icon>

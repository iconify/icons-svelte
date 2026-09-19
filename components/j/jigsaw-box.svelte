<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5g7j806z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f5g7j806z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:jigsaw-box" {...props}></Icon>

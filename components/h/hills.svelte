<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-hl833tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-hl833tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hills" {...props}></Icon>

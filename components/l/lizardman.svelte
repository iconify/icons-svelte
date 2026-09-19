<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzv2y_5jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fzv2y_5jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lizardman" {...props}></Icon>

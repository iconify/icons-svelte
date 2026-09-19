<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei7q5jb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ei7q5jb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:armor-downgrade" {...props}></Icon>

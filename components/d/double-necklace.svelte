<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9wnwxbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j9wnwxbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:double-necklace" {...props}></Icon>

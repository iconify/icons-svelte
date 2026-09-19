<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0k9_tb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f0k9_tb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:book-storm" {...props}></Icon>

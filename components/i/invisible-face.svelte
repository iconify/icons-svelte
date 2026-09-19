<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3o1v-b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b3o1v-b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:invisible-face" {...props}></Icon>

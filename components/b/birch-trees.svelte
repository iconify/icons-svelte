<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1rui8bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1rui8bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:birch-trees" {...props}></Icon>

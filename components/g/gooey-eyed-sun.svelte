<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu1dbkyxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bu1dbkyxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gooey-eyed-sun" {...props}></Icon>

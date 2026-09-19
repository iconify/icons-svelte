<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo25o29sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vo25o29sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:jigsaw-piece" {...props}></Icon>

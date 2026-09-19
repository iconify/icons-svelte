<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-vzh8b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x-vzh8b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:recycle" {...props}></Icon>

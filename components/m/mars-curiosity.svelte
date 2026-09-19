<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-mxhdbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y-mxhdbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mars-curiosity" {...props}></Icon>

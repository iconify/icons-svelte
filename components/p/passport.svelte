<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a71ialb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a71ialb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:passport" {...props}></Icon>

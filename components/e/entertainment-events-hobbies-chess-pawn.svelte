<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h16ti1b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h16ti1b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:entertainment-events-hobbies-chess-pawn" {...props}></Icon>

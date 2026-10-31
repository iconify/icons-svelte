<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayzsdqbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ayzsdqbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-gabled-building-with-flag-and-door" {...props}></Icon>

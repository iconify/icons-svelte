<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf6-8eb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rf6-8eb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hearts" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jscegrves.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jscegrves"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paranoia" {...props}></Icon>

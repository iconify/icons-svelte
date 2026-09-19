<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6l8o5b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r6l8o5b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:infinity" {...props}></Icon>

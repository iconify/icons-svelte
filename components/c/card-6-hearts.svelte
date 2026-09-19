<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnh5l98-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gnh5l98-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-6-hearts" {...props}></Icon>

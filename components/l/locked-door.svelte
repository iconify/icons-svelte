<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n95_fnbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n95_fnbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:locked-door" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moa--4apo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="moa--4apo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:boombox" {...props}></Icon>

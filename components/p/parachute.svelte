<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhi296bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dhi296bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:parachute" {...props}></Icon>

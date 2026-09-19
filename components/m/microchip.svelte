<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df8vl5s_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="df8vl5s_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:microchip" {...props}></Icon>

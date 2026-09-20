<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr08b61pk.css';
import '../../css/t/tjfi85b2h.css';
import '../../css/j/jyx3upbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="hr08b61pk"/><path class="tjfi85b2h"/><path class="jyx3upbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lollypop-music-player" {...props}></Icon>

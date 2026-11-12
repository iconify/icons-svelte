<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr08b61pk.css';
import '../../css/d/d_fvrmbcp.css';
import '../../css/v/v2um02b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="hr08b61pk"/><path class="d_fvrmbcp"/><path class="v2um02b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lollypop-music-player" {...props}></Icon>

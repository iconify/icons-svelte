<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tib28zb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tib28zb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ringing-alarm" {...props}></Icon>

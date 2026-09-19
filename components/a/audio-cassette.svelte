<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwfg2eecu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vwfg2eecu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:audio-cassette" {...props}></Icon>

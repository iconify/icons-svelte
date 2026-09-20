<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc5c167yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fc5c167yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:record-player-remix" {...props}></Icon>

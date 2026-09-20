<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra_mhhb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ra_mhhb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:fastforward-clock-remix" {...props}></Icon>

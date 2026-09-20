<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfqdlls5m.css';
import '../../css/u/uhxg3ozyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":250,"height":250};
const content = `<path class="nfqdlls5m"/><path class="uhxg3ozyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:charles-schwab" {...props}></Icon>

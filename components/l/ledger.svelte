<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnbe30brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":383,"height":128};
const content = `<path class="vnbe30brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ledger" {...props}></Icon>

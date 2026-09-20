<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3skxo8_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i3skxo8_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:control-d" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q86g-lw1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q86g-lw1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:media-record" {...props}></Icon>

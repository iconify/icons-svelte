<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3b2fn1ti.css';
import '../../css/i/i_b6kebet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="r3b2fn1ti"/><path class="i_b6kebet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:download" {...props}></Icon>

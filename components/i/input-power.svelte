<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pun54bbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pun54bbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:input-power" {...props}></Icon>

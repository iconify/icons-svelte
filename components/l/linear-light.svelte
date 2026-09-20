<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rebpobb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rebpobb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linear-light" {...props}></Icon>

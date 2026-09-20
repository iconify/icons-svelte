<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1b04pzpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q1b04pzpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:barcode-buddy-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/calya5bxg.css';
import '../../css/d/dq8f9xsoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="calya5bxg"/><path class="dq8f9xsoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center" {...props}></Icon>

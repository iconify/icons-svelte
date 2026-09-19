<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp97lfoxd.css';
import '../../css/k/k3ypocbdl.css';
import '../../css/t/tspdbdasy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="rp97lfoxd"><path clip-rule="evenodd" class="k3ypocbdl"/><path class="tspdbdasy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:pause" {...props}></Icon>

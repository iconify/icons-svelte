<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y1v0o7p4n.css';
import '../../css/s/s6n-b1uit.css';
import '../../css/y/ysgw9dbgp.css';
import '../../css/q/qu8h5d4df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="y1v0o7p4n"/><path class="s6n-b1uit"/><path class="ysgw9dbgp"/><path class="qu8h5d4df"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bell-slash-duo" {...props}></Icon>

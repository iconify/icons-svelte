<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvpxr2b8r.css';
import '../../css/u/u13r1zb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yvpxr2b8r"/><path class="u13r1zb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:patchmon" {...props}></Icon>

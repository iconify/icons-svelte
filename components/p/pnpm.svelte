<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2bteufbr.css';
import '../../css/p/p26pkt_uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a2bteufbr"/><path class="p26pkt_uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:pnpm" {...props}></Icon>

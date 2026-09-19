<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/on2p_wi5n.css';
import '../../css/v/v3y-9vz7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="on2p_wi5n"/><path clip-rule="evenodd" class="v3y-9vz7f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:rolling-eyes-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/b/b3zk9cc4a.css';
import '../../css/t/tyk4bm_5n.css';
import '../../css/d/d_jqz1j2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="b3zk9cc4a"/><path class="tyk4bm_5n"/><path class="d_jqz1j2x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-middle" {...props}></Icon>

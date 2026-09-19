<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/b/b3zk9cc4a.css';
import '../../css/q/qma2srvwk.css';
import '../../css/n/ntqhod3mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="b3zk9cc4a"/><path class="qma2srvwk"/><path class="ntqhod3mp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-africa" {...props}></Icon>

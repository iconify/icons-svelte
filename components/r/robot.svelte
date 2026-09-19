<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/k/k-y9zgp3c.css';
import '../../css/e/ebpla5b_i.css';
import '../../css/b/brg541bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="k-y9zgp3c"/><path class="ebpla5b_i"/><path class="brg541bpm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:robot" {...props}></Icon>

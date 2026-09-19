<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/if4zyybqp.css';
import '../../css/k/kag6sfpgh.css';
import '../../css/n/nb181ei5f.css';
import '../../css/v/vlh_t3w3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="if4zyybqp"/><path class="kag6sfpgh"/><path class="nb181ei5f"/><path class="vlh_t3w3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lock-open-1-outline" {...props}></Icon>

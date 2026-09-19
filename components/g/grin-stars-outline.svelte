<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/v/v1kv4f3wb.css';
import '../../css/n/ni8xmk99j.css';
import '../../css/s/si2jfabzm.css';
import '../../css/z/zt1e34j_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="v1kv4f3wb"/><path class="ni8xmk99j"/><path class="si2jfabzm"/><path class="zt1e34j_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grin-stars-outline" {...props}></Icon>

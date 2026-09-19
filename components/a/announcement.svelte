<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/i/i_79_gb5t.css';
import '../../css/w/wbug46-jv.css';
import '../../css/y/y3dt-zlek.css';
import '../../css/z/zhj5w-a4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="i_79_gb5t"/><path class="wbug46-jv"/><path class="y3dt-zlek"/><path class="zhj5w-a4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:announcement" {...props}></Icon>

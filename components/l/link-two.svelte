<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/z/zxrxabb7c.css';
import '../../css/a/ajq-sm9bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="zxrxabb7c"/><path class="ajq-sm9bk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:link-two" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/y/y6f0jibvm.css';
import '../../css/j/j3iodsbfd.css';
import '../../css/h/hv36otb5b.css';
import '../../css/k/k86bz2btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="y6f0jibvm"/><path class="j3iodsbfd"/><path class="hv36otb5b"/><path class="k86bz2btu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:record-disc" {...props}></Icon>

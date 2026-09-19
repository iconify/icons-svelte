<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/b/baen2yhxr.css';
import '../../css/h/hjeu-zbtf.css';
import '../../css/n/neptv8bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="baen2yhxr"/><circle class="hjeu-zbtf"/><path class="neptv8bgx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:compass" {...props}></Icon>

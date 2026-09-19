<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cvmkqsbso.css';
import '../../css/j/jzmvxfbwd.css';
import '../../css/k/kcitn8s2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="cvmkqsbso"/><path clip-rule="evenodd" class="jzmvxfbwd"/><path clip-rule="evenodd" class="kcitn8s2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:hpv-outline" {...props}></Icon>

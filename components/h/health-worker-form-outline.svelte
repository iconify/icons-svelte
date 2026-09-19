<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zefpa7icl.css';
import '../../css/a/ahjnos-qj.css';
import '../../css/d/djzed1b0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="zefpa7icl"/><path clip-rule="evenodd" class="ahjnos-qj"/><path clip-rule="evenodd" class="djzed1b0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:health-worker-form-outline" {...props}></Icon>

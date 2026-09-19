<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/g/gvwzbcc6a.css';
import '../../css/u/u3czx2-4f.css';
import '../../css/g/gatnvbbxy.css';
import '../../css/a/a12qccc1u.css';
import '../../css/b/bvmag0xgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="gvwzbcc6a"/><path class="u3czx2-4f"/><path class="gatnvbbxy"/><circle class="a12qccc1u"/><circle class="bvmag0xgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:makeups" {...props}></Icon>

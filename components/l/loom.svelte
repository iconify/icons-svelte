<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xkcbbrbzm.css';
import '../../css/m/md286fbip.css';
import '../../css/a/afxenvblv.css';
import '../../css/z/zhnu5sbcn.css';
import '../../css/p/pcp1pubtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="xkcbbrbzm"/><g class="md286fbip"><path class="afxenvblv"/><path class="zhnu5sbcn"/><path class="pcp1pubtx"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:loom" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xu20nsb-w.css';
import '../../css/h/h220zcbfh.css';
import '../../css/e/e_4x7sb2e.css';
import '../../css/i/iql33bbkv.css';
import '../../css/o/ow275bckj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="xu20nsb-w"/><path class="h220zcbfh"/><path class="e_4x7sb2e"/><path clip-rule="evenodd" class="iql33bbkv"/><path class="ow275bckj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:plug" {...props}></Icon>

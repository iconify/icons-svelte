<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bx4b2bx_u.css';
import '../../css/g/gp_vt1wen.css';
import '../../css/p/p_xts3q8k.css';
import '../../css/k/kfg5rls2d.css';
import '../../css/z/zkm2qjb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="bx4b2bx_u"/><path class="gp_vt1wen"/><path class="p_xts3q8k"/><path clip-rule="evenodd" class="kfg5rls2d"/><path clip-rule="evenodd" class="zkm2qjb4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:red-envelope" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/k/kgr9m0bmi.css';
import '../../css/x/xd0veabmf.css';
import '../../css/n/n3jvmegul.css';
import '../../css/e/e1dpwnbcb.css';
import '../../css/a/a0o9nky4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="kgr9m0bmi"/><path class="wm-shine xd0veabmf"/><path class="n3jvmegul wm-k"/><path class="e1dpwnbcb wm-a"/><path class="a0o9nky4v wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:file-minus" {...props}></Icon>

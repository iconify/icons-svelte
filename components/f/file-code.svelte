<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/g/g9mt46brz.css';
import '../../css/x/xd0veabmf.css';
import '../../css/n/n3jvmegul.css';
import '../../css/m/mckl6xbbj.css';
import '../../css/a/a0o9nky4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="g9mt46brz"/><path class="wm-shine xd0veabmf"/><path class="n3jvmegul wm-k"/><path class="mckl6xbbj wm-a"/><path class="a0o9nky4v wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:file-code" {...props}></Icon>

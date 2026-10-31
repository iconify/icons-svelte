<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/d/dpndwwtgs.css';
import '../../css/m/mml7skbfj.css';
import '../../css/b/bht756bnp.css';
import '../../css/g/g136touho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="dpndwwtgs"/><path class="mml7skbfj wm-shine"/><path class="bht756bnp wm-k"/><path class="g136touho wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:app-window" {...props}></Icon>

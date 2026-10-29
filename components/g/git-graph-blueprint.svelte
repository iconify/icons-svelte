<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/hltawnn4f.css';
import '../../css/k/kzv9qkbxl.css';
import '../../css/t/t218te2ox.css';
import '../../css/g/gk_fs1s3s.css';
import '../../css/f/fhmv5bbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="hltawnn4f wm-deco"/><path class="kzv9qkbxl wm-deco"/><path class="t218te2ox wm-deco"/><path class="gk_fs1s3s wm-k"/><path class="fhmv5bbjb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-graph-blueprint" {...props}></Icon>

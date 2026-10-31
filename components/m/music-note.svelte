<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/s/sivfj3bof.css';
import '../../css/r/rb5emwb6v.css';
import '../../css/g/gle5llb7u.css';
import '../../css/r/rh9qoibkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="sivfj3bof"/><path class="rb5emwb6v wm-shine"/><path class="gle5llb7u"/><path class="rh9qoibkn wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:music-note" {...props}></Icon>

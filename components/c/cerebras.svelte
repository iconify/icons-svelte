<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzxkiu5ie.css';
import '../../css/x/xpa0b3bpk.css';
import '../../css/j/jt3_xabug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pzxkiu5ie"><path clip-rule="evenodd" class="xpa0b3bpk"/><path class="jt3_xabug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cerebras" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f4lfqelzl.css';
import '../../css/v/vncdglbxf.css';
import '../../css/d/dj6hz0ywu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f4lfqelzl"/><path class="vncdglbxf"/><path class="dj6hz0ywu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-key-object" {...props}></Icon>

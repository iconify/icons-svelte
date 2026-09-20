<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gbi35-b1q.css';
import '../../css/f/fafky8odj.css';
import '../../css/l/lgp6ae1_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gbi35-b1q"/><path class="fafky8odj"/><path class="lgp6ae1_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:note-square-filled" {...props}></Icon>

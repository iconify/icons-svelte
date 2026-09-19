<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iy3rf6ewf.css';
import '../../css/m/m8wbj0b5b.css';
import '../../css/y/y63x79b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="iy3rf6ewf"/><path class="m8wbj0b5b"/><path clip-rule="evenodd" class="y63x79b_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:rightwards-pushing-hand" {...props}></Icon>

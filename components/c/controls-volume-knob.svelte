<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/h/h9o4z3bkr.css';
import '../../css/n/nanjsmb7e.css';
import '../../css/o/oiuzdwzyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="h9o4z3bkr"/><path class="nanjsmb7e"/><path class="oiuzdwzyw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:controls-volume-knob" {...props}></Icon>

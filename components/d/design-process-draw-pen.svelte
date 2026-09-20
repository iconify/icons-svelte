<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o25gd6bvp.css';
import '../../css/v/vhqxg0bai.css';
import '../../css/u/ue554cbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o25gd6bvp"/><path class="vhqxg0bai"/><path class="ue554cbvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:design-process-draw-pen" {...props}></Icon>

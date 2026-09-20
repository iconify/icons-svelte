<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gxpqwabxe.css';
import '../../css/m/mn-c1gvts.css';
import '../../css/d/d82kh5btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gxpqwabxe"/><path class="mn-c1gvts"/><path class="d82kh5btl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:business-metaphor-boat-success" {...props}></Icon>

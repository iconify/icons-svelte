<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sb8lcabgc.css';
import '../../css/c/c-hho8xra.css';
import '../../css/o/ow1qj4p-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sb8lcabgc"/><path class="c-hho8xra"/><path class="ow1qj4p-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:programming-language-bookmark-javascript" {...props}></Icon>

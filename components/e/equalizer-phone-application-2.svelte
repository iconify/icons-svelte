<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/puw9pfmix.css';
import '../../css/r/rxtl2ibrn.css';
import '../../css/a/ao_0jqt1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="puw9pfmix"/><path class="rxtl2ibrn"/><path class="ao_0jqt1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:equalizer-phone-application-2" {...props}></Icon>

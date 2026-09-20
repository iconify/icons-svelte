<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/i_cyoebni.css';
import '../../css/v/v3gtaabgc.css';
import '../../css/f/ff_c_uz4c.css';
import '../../css/t/tr5lgkb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="i_cyoebni"/><path class="v3gtaabgc"/><path class="ff_c_uz4c"/><path class="tr5lgkb8t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:podcast-microphone-international-1" {...props}></Icon>

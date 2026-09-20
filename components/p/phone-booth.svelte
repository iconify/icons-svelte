<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/h/h2i4iib3s.css';
import '../../css/w/wdfe82b4z.css';
import '../../css/s/sz507lblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="h2i4iib3s"/><path class="wdfe82b4z"/><path class="sz507lblu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:phone-booth" {...props}></Icon>

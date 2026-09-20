<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x3o7b8xqv.css';
import '../../css/d/duazxfbrd.css';
import '../../css/a/a2zd00mlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x3o7b8xqv"/><path class="duazxfbrd"/><path class="a2zd00mlc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:drawer-download" {...props}></Icon>

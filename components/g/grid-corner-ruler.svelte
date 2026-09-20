<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/p18lntbms.css';
import '../../css/z/zqgxlpbyx.css';
import '../../css/i/i73p8iv3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="p18lntbms"/><path class="zqgxlpbyx"/><path class="i73p8iv3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:grid-corner-ruler" {...props}></Icon>

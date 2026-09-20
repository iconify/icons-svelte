<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gelqftbbq.css';
import '../../css/b/buckucclw.css';
import '../../css/d/dv996mu9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gelqftbbq"/><path class="buckucclw"/><path class="dv996mu9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:amusement-park-castle" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gjccdsbql.css';
import '../../css/s/sqzg-pbzs.css';
import '../../css/d/dxs3hib_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gjccdsbql"/><path class="sqzg-pbzs"/><path class="dxs3hib_h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:business-metaphor-lucky-cat" {...props}></Icon>

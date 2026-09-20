<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xjecwpb6j.css';
import '../../css/f/fnick3f-z.css';
import '../../css/v/v9pdm5hvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xjecwpb6j"/><path class="fnick3f-z"/><path class="v9pdm5hvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:hierarchy-web" {...props}></Icon>

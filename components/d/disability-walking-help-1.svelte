<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/ncmy087qb.css';
import '../../css/h/h8fxcw__y.css';
import '../../css/e/e41xnvung.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ncmy087qb"/><path class="h8fxcw__y"/><path class="e41xnvung"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:disability-walking-help-1" {...props}></Icon>

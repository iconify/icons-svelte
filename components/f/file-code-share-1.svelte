<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/kdqvh6bbb.css';
import '../../css/v/v7fyv2tmw.css';
import '../../css/e/ew1tkbrtr.css';
import '../../css/g/gn_t_acog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="kdqvh6bbb"/><path class="v7fyv2tmw"/><path class="ew1tkbrtr"/><path class="gn_t_acog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:file-code-share-1" {...props}></Icon>

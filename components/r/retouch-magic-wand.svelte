<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gkddejbjm.css';
import '../../css/m/m0xu3lb3d.css';
import '../../css/e/ekppvbc7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gkddejbjm"/><path class="m0xu3lb3d"/><path class="ekppvbc7w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:retouch-magic-wand" {...props}></Icon>

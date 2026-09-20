<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hliel1b1l.css';
import '../../css/p/p-b21_k3d.css';
import '../../css/a/au1i4acjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hliel1b1l"/><path class="p-b21_k3d"/><path class="au1i4acjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:allowances-no-photos-sign" {...props}></Icon>

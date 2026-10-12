<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p7il8qmhh.css';
import '../../css/l/le910wibb.css';
import '../../css/t/t1nuh1b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="p7il8qmhh"/><circle transform="rotate(90 12 12)" class="le910wibb"/><path class="t1nuh1b-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:crosshair" {...props}></Icon>

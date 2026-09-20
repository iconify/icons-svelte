<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zv1da0btv.css';
import '../../css/p/p4ymsz41h.css';
import '../../css/k/kuyexsk0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zv1da0btv"/><path class="p4ymsz41h"/><path class="kuyexsk0s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:desktop-action-monitor-add" {...props}></Icon>

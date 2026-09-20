<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f8hzo4ber.css';
import '../../css/y/y98xg9blh.css';
import '../../css/y/ye_46gv7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="f8hzo4ber"/><path class="y98xg9blh"/><path class="ye_46gv7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:desktop-action-monitor-question" {...props}></Icon>

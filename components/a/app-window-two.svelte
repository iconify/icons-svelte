<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t-ohslb4m.css';
import '../../css/d/dklgphbkr.css';
import '../../css/t/tjas9wbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="t-ohslb4m"/><path class="dklgphbkr"/><path class="tjas9wbhh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:app-window-two" {...props}></Icon>

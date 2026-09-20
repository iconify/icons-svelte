<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t03zpmbmc.css';
import '../../css/g/gj580ybou.css';
import '../../css/i/iirl5cb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="t03zpmbmc"/><path class="gj580ybou"/><path class="iirl5cb_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:memory-sd-card-search" {...props}></Icon>

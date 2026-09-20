<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/v/v_x0netdn.css';
import '../../css/o/ohqjceyzq.css';
import '../../css/u/uw1b0vb0b.css';
import '../../css/q/qibn-ebyb.css';
import '../../css/t/t6strnb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="v_x0netdn"/><path class="ohqjceyzq"/><path class="uw1b0vb0b"/><path class="qibn-ebyb"/><path class="t6strnb3i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:receipt-view-pricing" {...props}></Icon>

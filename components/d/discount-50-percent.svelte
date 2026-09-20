<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hbl_i6buq.css';
import '../../css/q/q8ea5g2bk.css';
import '../../css/e/ei4x3rbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hbl_i6buq"/><path class="q8ea5g2bk"/><path class="ei4x3rbqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:discount-50-percent" {...props}></Icon>

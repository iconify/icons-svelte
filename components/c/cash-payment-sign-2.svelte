<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yyptcnxel.css';
import '../../css/w/w4l--qbhc.css';
import '../../css/u/ut33svvhu.css';
import '../../css/c/c_rt07bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yyptcnxel"/><path class="w4l--qbhc"/><path class="ut33svvhu"/><path class="c_rt07bxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cash-payment-sign-2" {...props}></Icon>

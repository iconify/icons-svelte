<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gbeqjcbfp.css';
import '../../css/i/i6432t0ri.css';
import '../../css/w/wgzy--bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gbeqjcbfp"/><path class="i6432t0ri"/><path class="wgzy--bjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:modern-payment-desktop-transaction" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/ketgzibwl.css';
import '../../css/q/qeti59buh.css';
import '../../css/x/xqwhzubqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ketgzibwl"/><path class="qeti59buh"/><path class="xqwhzubqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:cashier-machine-2-flat" {...props}></Icon>

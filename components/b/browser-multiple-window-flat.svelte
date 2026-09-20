<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f0pe0unnb.css';
import '../../css/l/lhmq3gbqs.css';
import '../../css/e/e_r28dbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="f0pe0unnb"/><path class="lhmq3gbqs"/><path class="e_r28dbth"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:browser-multiple-window-flat" {...props}></Icon>

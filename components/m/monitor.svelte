<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/ttt_csb7t.css';
import '../../css/c/cnjv6tbhg.css';
import '../../css/n/ngw06abol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ttt_csb7t"/><path clip-rule="evenodd" class="cnjv6tbhg"/><path class="ngw06abol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:monitor" {...props}></Icon>

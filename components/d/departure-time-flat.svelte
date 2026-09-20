<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wfd-hn76v.css';
import '../../css/k/kb89oqhiv.css';
import '../../css/w/w1nza9b4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wfd-hn76v"/><path class="kb89oqhiv"/><path class="w1nza9b4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:departure-time-flat" {...props}></Icon>

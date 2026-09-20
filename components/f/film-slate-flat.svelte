<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/ut9dq2spn.css';
import '../../css/z/zquzsxtwc.css';
import '../../css/g/gb6yjacvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ut9dq2spn"/><path class="zquzsxtwc"/><path class="gb6yjacvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:film-slate-flat" {...props}></Icon>

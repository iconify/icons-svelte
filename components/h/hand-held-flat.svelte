<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tm7izd6wa.css';
import '../../css/j/jx1nbccqi.css';
import '../../css/y/ysuuyabkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tm7izd6wa"/><path class="jx1nbccqi"/><path class="ysuuyabkl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:hand-held-flat" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lwivuzb_u.css';
import '../../css/e/ehbqml5ic.css';
import '../../css/m/m_cyn06nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><circle class="lwivuzb_u"/><circle class="ehbqml5ic"/><circle class="m_cyn06nd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:dots-y" {...props}></Icon>

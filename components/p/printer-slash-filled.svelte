<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nayx7kq2s.css';
import '../../css/j/j77qtabfg.css';
import '../../css/s/s4mvm7bih.css';
import '../../css/u/u7b0qh3uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nayx7kq2s"/><path class="j77qtabfg"/><path class="s4mvm7bih"/><path class="u7b0qh3uk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:printer-slash-filled" {...props}></Icon>

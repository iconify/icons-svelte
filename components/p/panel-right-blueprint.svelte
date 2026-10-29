<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/at84-ubob.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/j/jv-k-dbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="at84-ubob wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="jv-k-dbpo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-right-blueprint" {...props}></Icon>

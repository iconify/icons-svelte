<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/j/jsd5p2bkd.css';
import '../../css/c/cr7efcbob.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/c/cb-t85bmb.css';
import '../../css/a/ajrx2wbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="jsd5p2bkd wm-deco"/><path class="cr7efcbob wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="cb-t85bmb"/><path class="ajrx2wbff"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:power-blueprint" {...props}></Icon>

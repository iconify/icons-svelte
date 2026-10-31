<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/d/dfr8kabwp.css';
import '../../css/o/omdwggbcq.css';
import '../../css/w/wcaq-jbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="dfr8kabwp wm-k"/><path class="omdwggbcq wm-a"/><path class="wcaq-jbkf wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:bitcoin" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/q/q3bgkubrx.css';
import '../../css/n/nv21rbpbn.css';
import '../../css/j/jmymbhwhv.css';
import '../../css/l/lmc0pzw-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="q3bgkubrx wm-shadow"/><path class="nv21rbpbn wm-shadow"/><path class="jmymbhwhv"/><path class="lmc0pzw-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:app-window" {...props}></Icon>

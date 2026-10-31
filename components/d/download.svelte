<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/p/pe-9es50i.css';
import '../../css/e/e4rf4ybtc.css';
import '../../css/b/b1yfy4bkn.css';
import '../../css/o/o-du-vbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="pe-9es50i wm-shadow"/><path class="e4rf4ybtc wm-shadow"/><path class="b1yfy4bkn"/><path class="o-du-vbfa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:download" {...props}></Icon>

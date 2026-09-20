<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gsukswb1w.css';
import '../../css/s/sxn4tfl2r.css';
import '../../css/y/yvzccrbbf.css';
import '../../css/g/gkqxq7xik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gsukswb1w"/><path class="sxn4tfl2r"/><path class="yvzccrbbf"/><path class="gkqxq7xik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:crypto-currency-bitcoin-network-globe" {...props}></Icon>

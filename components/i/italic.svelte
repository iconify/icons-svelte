<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/i/icgtmkcqv.css';
import '../../css/v/vgp1y8-te.css';
import '../../css/m/m0060_lza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="icgtmkcqv"/><path class="vgp1y8-te"/><path class="m0060_lza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:italic" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ick8o1b-y.css';
import '../../css/g/g40jultif.css';
import '../../css/g/g80rf7b8i.css';
import '../../css/t/tsu3ypo6o.css';
import '../../css/y/y6dum9mni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ick8o1b-y"/><path class="g40jultif"/><path class="g80rf7b8i"/><path class="tsu3ypo6o"/><path class="y6dum9mni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:floor-lamp-minimalistic-linear" {...props}></Icon>

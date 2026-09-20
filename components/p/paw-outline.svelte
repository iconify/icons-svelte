<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/ptqbabcmv.css';
import '../../css/m/mzy2mhzrn.css';
import '../../css/c/cdianvu6r.css';
import '../../css/v/vu5fr_lab.css';
import '../../css/t/t8dah2_ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ptqbabcmv"/><path class="mzy2mhzrn"/><path class="cdianvu6r"/><path class="vu5fr_lab"/><path class="t8dah2_ly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paw-outline" {...props}></Icon>

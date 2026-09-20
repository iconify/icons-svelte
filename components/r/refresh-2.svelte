<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/f/fznb90gae.css';
import '../../css/h/h3xk7ebgr.css';
import '../../css/s/slj-q6j2r.css';
import '../../css/p/pn1ky7q8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="fznb90gae"/><path class="h3xk7ebgr"/><path class="slj-q6j2r"/><path class="pn1ky7q8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:refresh-2" {...props}></Icon>

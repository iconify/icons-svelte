<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wdl10clxd.css';
import '../../css/e/e0qg3-blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="wdl10clxd"/><path class="e0qg3-blf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:camera-1" {...props}></Icon>

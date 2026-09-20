<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bohz0aboj.css';
import '../../css/g/gegijw-bc.css';
import '../../css/k/kvlujpe3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="bohz0aboj"/><path class="gegijw-bc"/><path class="kvlujpe3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arc-browser" {...props}></Icon>

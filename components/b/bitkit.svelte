<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/l_e55p-ia.css';
import '../../css/y/yizg1nbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="l_e55p-ia"/><path class="yizg1nbwt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bitkit" {...props}></Icon>

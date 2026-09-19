<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/o7go62bvs.css';
import '../../css/r/r74jfkeku.css';
import '../../css/w/wtwsfcbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="o7go62bvs"/><path class="r74jfkeku"/><path class="wtwsfcbkl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:arrow-right" {...props}></Icon>

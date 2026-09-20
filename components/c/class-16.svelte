<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/phdx6-bmp.css';
import '../../css/d/d9zq3rwql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="phdx6-bmp"/><path class="d9zq3rwql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:class-16" {...props}></Icon>

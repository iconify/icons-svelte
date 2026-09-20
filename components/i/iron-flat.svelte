<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/h/htnqktrsj.css';
import '../../css/x/xbsov-i1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="htnqktrsj"/><path class="xbsov-i1f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:iron-flat" {...props}></Icon>

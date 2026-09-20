<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zf0gm4int.css';
import '../../css/u/u17sczo3a.css';
import '../../css/z/z1idorbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zf0gm4int"/><path class="u17sczo3a"/><path class="z1idorbcj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:fireworks-rocket-flat" {...props}></Icon>

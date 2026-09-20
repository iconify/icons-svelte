<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/uj4dlhj0o.css';
import '../../css/j/jg34bubij.css';
import '../../css/c/cdbkuu2ld.css';
import '../../css/y/ykniiz8fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="uj4dlhj0o"/><path class="jg34bubij"/><path class="cdbkuu2ld"/><path class="ykniiz8fo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:calculator-2-flat" {...props}></Icon>

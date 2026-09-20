<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wpdy7_m7a.css';
import '../../css/c/c585gybuh.css';
import '../../css/p/pyalcp8zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wpdy7_m7a"/><path class="c585gybuh"/><path class="pyalcp8zz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:pork-meat-flat" {...props}></Icon>

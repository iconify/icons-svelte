<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/u/u9p4c4uvm.css';
import '../../css/c/cd636xjdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="u9p4c4uvm"/><path class="cd636xjdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:lock-rotation-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/d/dvz55bbxk.css';
import '../../css/t/tcl4vzbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="dvz55bbxk"/><path class="tcl4vzbmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:inbox-lock-solid" {...props}></Icon>

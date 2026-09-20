<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lk-0jbc2x.css';
import '../../css/n/nsb12sb4m.css';
import '../../css/y/y8b9a08tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lk-0jbc2x"/><path class="nsb12sb4m"/><path class="y8b9a08tb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:politics-speech-flat" {...props}></Icon>

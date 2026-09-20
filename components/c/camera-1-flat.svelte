<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/o/ombox1bmp.css';
import '../../css/i/io90tpb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ombox1bmp"/><path class="io90tpb-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:camera-1-flat" {...props}></Icon>

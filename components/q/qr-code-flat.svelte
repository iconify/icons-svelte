<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/krcelihbz.css';
import '../../css/n/n76sdzv2k.css';
import '../../css/q/q44e-r43q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="krcelihbz"/><path class="n76sdzv2k"/><path class="q44e-r43q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:qr-code-flat" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k955_kc5q.css';
import '../../css/b/bvi56cb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="k955_kc5q"/><path clip-rule="evenodd" class="bvi56cb7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:chat-bubble-square-write-flat" {...props}></Icon>

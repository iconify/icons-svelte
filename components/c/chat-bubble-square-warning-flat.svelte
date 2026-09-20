<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hk6kc4b6f.css';
import '../../css/s/smxec20gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hk6kc4b6f"/><path class="smxec20gl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:chat-bubble-square-warning-flat" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/p/pk2dj7b8n.css';
import '../../css/d/d9iih56zc.css';
import '../../css/l/lmlsjm30a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="pk2dj7b8n"/><path clip-rule="evenodd" class="d9iih56zc"/><path class="lmlsjm30a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:chess-king" {...props}></Icon>

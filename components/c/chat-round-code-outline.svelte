<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cu9odw3qy.css';
import '../../css/c/cxqjcctvs.css';
import '../../css/a/a44ytmbfp.css';
import '../../css/m/m_goimbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cu9odw3qy"/><path class="cxqjcctvs"/><path class="a44ytmbfp"/><path clip-rule="evenodd" class="m_goimbsb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-code-outline" {...props}></Icon>

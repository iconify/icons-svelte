<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fhpl0-3an.css';
import '../../css/l/lz4m_yb4l.css';
import '../../css/z/zlzxvdb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fhpl0-3an"/><path clip-rule="evenodd" class="lz4m_yb4l"/><path clip-rule="evenodd" class="zlzxvdb5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:rewind-10s-duotone" {...props}></Icon>

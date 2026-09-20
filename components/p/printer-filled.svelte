<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n8sovnz4j.css';
import '../../css/o/obpt3dxcu.css';
import '../../css/u/u97m_wqmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="n8sovnz4j"/><path class="obpt3dxcu"/><path clip-rule="evenodd" class="u97m_wqmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:printer-filled" {...props}></Icon>

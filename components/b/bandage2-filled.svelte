<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zd2s8xmoy.css';
import '../../css/z/zdh_jsyip.css';
import '../../css/u/ude1m_b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zd2s8xmoy"/><path clip-rule="evenodd" class="zdh_jsyip"/><path class="ude1m_b4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bandage2-filled" {...props}></Icon>

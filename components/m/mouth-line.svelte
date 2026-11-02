<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_wxui_qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_wxui_qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mouth-line" {...props}></Icon>

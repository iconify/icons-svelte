<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/ws7tt80dx.css';
import '../../css/u/ufw1mbb_w.css';
import '../../css/m/mphyl5x1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ws7tt80dx"/><path class="ufw1mbb_w"/><path class="mphyl5x1f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chat-preview-01" {...props}></Icon>

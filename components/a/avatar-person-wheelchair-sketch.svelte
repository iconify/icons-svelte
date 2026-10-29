<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gt1o1xisn.css';
import '../../css/z/zuzzs3bke.css';
import '../../css/o/ot4dkg9sh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gt1o1xisn wm-a"/><path class="wm-k zuzzs3bke"/><path class="ot4dkg9sh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-person-wheelchair-sketch" {...props}></Icon>

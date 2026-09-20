<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu_w7xh2p.css';
import '../../css/l/lmrkdploq.css';
import '../../css/s/sawgbjh1b.css';
import '../../css/m/molxzo9aq.css';
import '../../css/g/ggmdoxbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu_w7xh2p"/><path class="lmrkdploq"/><path class="sawgbjh1b"/><path class="molxzo9aq"/><path clip-rule="evenodd" class="ggmdoxbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lazio" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/unez3en8j.css';
import '../../css/n/nvv_c9j-h.css';
import '../../css/a/anw3ijuct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="unez3en8j"/><path class="nvv_c9j-h wm-shadow"/><path class="anw3ijuct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lamp-engrave" {...props}></Icon>

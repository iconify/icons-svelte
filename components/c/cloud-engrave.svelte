<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/do26crbva.css';
import '../../css/f/ftut6hr7j.css';
import '../../css/c/cvilh7buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="do26crbva"/><path class="ftut6hr7j wm-shadow"/><path class="cvilh7buk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-engrave" {...props}></Icon>

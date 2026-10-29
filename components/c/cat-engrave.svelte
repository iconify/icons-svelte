<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v_hbawbgh.css';
import '../../css/r/rr05tdbqi.css';
import '../../css/f/f0_ic289c.css';
import '../../css/a/ac1m7ezbo.css';
import '../../css/h/h4vcpvbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v_hbawbgh wm-k"/><path class="rr05tdbqi wm-a"/><path class="f0_ic289c wm-shadow"/><path class="ac1m7ezbo wm-k"/><path class="h4vcpvbdh wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cat-engrave" {...props}></Icon>

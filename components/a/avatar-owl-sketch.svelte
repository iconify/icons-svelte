<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/go7m5qb9b.css';
import '../../css/j/jfnbg6t3e.css';
import '../../css/b/b5iz41bba.css';
import '../../css/g/gkbm3cc5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="go7m5qb9b"/><path class="jfnbg6t3e wm-k"/><path class="b5iz41bba wm-k"/><path class="gkbm3cc5v wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-owl-sketch" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v-483rb4t.css';
import '../../css/g/g2wwaeb3g.css';
import '../../css/b/b2sz1838t.css';
import '../../css/b/b5jcl5blk.css';
import '../../css/x/xk6eoibzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v-483rb4t wm-k"/><path class="g2wwaeb3g wm-a"/><path class="b2sz1838t wm-shadow"/><path class="b5jcl5blk wm-k"/><path class="wm-a xk6eoibzj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:person-standing-engrave" {...props}></Icon>

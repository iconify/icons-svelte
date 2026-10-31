<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/c/cntbxxb-u.css';
import '../../css/g/gxv26u8uu.css';
import '../../css/x/xoxv71b8a.css';
import '../../css/n/n_f1wwbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="cntbxxb-u wm-shadow"/><path class="gxv26u8uu wm-shadow"/><path class="xoxv71b8a"/><path class="n_f1wwbjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:door-open" {...props}></Icon>

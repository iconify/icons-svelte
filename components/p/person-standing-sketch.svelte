<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fpmz6qgbp.css';
import '../../css/d/dmvw43b8a.css';
import '../../css/u/ul8icbcwx.css';
import '../../css/g/glqwjopdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fpmz6qgbp wm-k"/><path class="dmvw43b8a wm-a"/><path class="ul8icbcwx wm-k"/><path class="glqwjopdo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:person-standing-sketch" {...props}></Icon>

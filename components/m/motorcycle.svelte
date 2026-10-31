<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lsi9_rb6t.css';
import '../../css/n/nu7q2clxj.css';
import '../../css/q/qguy_lbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lsi9_rb6t wm-shadow"/><path class="nu7q2clxj wm-shadow"/><path class="qguy_lbsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:motorcycle" {...props}></Icon>

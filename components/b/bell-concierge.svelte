<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/q/qds7mmgln.css';
import '../../css/u/u2_wjkb4f.css';
import '../../css/q/qew44nber.css';
import '../../css/k/kp4u9nbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="qds7mmgln wm-shadow"/><path class="u2_wjkb4f wm-shadow"/><path class="qew44nber"/><path class="kp4u9nbgh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:bell-concierge" {...props}></Icon>

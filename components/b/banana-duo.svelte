<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hol610bkj.css';
import '../../css/v/vxyac5iur.css';
import '../../css/o/ow5u1cc8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hol610bkj"/><path class="vxyac5iur wm-a"/><path class="ow5u1cc8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:banana-duo" {...props}></Icon>

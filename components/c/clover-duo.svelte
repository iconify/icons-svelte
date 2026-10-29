<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xe3jmcb9i.css';
import '../../css/i/ii4t2pmgx.css';
import '../../css/z/zki05l2_a.css';
import '../../css/r/r6zdo0mwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xe3jmcb9i"/><path class="ii4t2pmgx"/><path class="wm-a zki05l2_a"/><path class="r6zdo0mwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clover-duo" {...props}></Icon>

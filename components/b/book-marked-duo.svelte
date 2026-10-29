<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/umh6vabqg.css';
import '../../css/k/kwybaobhx.css';
import '../../css/j/jfb-yjbgw.css';
import '../../css/q/qaz17vbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="umh6vabqg"/><path class="kwybaobhx wm-a"/><path class="jfb-yjbgw"/><path class="qaz17vbsh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:book-marked-duo" {...props}></Icon>

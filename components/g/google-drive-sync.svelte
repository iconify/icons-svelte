<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/kk2njkbuf.css';
import '../../css/q/qo1f1obln.css';
import '../../css/b/bhgumod8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kk2njkbuf"/><path class="qo1f1obln"/><path class="bhgumod8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:google-drive-sync" {...props}></Icon>

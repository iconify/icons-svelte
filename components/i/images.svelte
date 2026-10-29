<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b8gdax63a.css';
import '../../css/u/u11d_bcbf.css';
import '../../css/j/j3ihixg7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b8gdax63a"/><path class="u11d_bcbf"/><path class="j3ihixg7r wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:images" {...props}></Icon>

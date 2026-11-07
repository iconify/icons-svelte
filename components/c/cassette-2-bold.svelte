<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar3grmbxb.css';
import '../../css/o/ohscxxbjx.css';
import '../../css/x/x0ga9cfcw.css';
import '../../css/o/o7fi5_bdy.css';
import '../../css/q/qwupe9yaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar3grmbxb"/><path class="ohscxxbjx"/><path class="x0ga9cfcw"/><path clip-rule="evenodd" class="o7fi5_bdy"/><path class="qwupe9yaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cassette-2-bold" {...props}></Icon>

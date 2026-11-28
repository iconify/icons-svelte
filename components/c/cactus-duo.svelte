<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6plzccju.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/iqpj3cywr.css';
import '../../css/x/xvgwadc1r.css';
import '../../css/n/nxx61nbqr.css';
import '../../css/j/jptgulbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary z6plzccju"/><g class="dt0cm9dhy primary"><path class="iqpj3cywr"/><path class="xvgwadc1r"/><path class="nxx61nbqr"/><path class="jptgulbjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cactus-duo" {...props}></Icon>

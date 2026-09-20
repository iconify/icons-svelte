<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/q/qgeq1yd2g.css';
import '../../css/u/u07j1sc6s.css';
import '../../css/g/g1h9-5bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="qgeq1yd2g"/><path class="u07j1sc6s"/><path class="g1h9-5bhu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:file-dock" {...props}></Icon>

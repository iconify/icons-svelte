<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wr6slzm6t.css';
import '../../css/f/fpth1bb7p.css';
import '../../css/e/ebjwlsagl.css';
import '../../css/v/vhcww73cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":19,"height":32};
const content = `<g class="cuyn6tgcc"><path class="wr6slzm6t"/><path class="fpth1bb7p"/><circle class="ebjwlsagl"/><path class="vhcww73cv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:phone" {...props}></Icon>

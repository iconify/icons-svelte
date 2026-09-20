<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n0gc8jbdr.css';
import '../../css/r/rd-rd7bad.css';
import '../../css/b/bccuqhbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n0gc8jbdr"/><path class="rd-rd7bad"/><path class="bccuqhbvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bluetooth-wave-duotone" {...props}></Icon>

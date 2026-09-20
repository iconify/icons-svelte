<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/e5jfzabtj.css';
import '../../css/p/p0g2tac2m.css';
import '../../css/b/bsf2wtbwe.css';
import '../../css/z/z5o8yvb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e5jfzabtj"/><path class="p0g2tac2m"/><path class="bsf2wtbwe"/><path class="z5o8yvb-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-wind-turbine" {...props}></Icon>

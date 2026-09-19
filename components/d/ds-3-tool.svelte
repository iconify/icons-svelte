<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/njny9tb1g.css';
import '../../css/k/k710rqb2o.css';
import '../../css/l/lnitt9mus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="njny9tb1g"/><path class="k710rqb2o"/><path class="lnitt9mus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ds-3-tool" {...props}></Icon>

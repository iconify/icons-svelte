<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m9huq1jph.css';
import '../../css/a/auhfmn4jd.css';
import '../../css/x/xsr2o7bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="m9huq1jph"/><path class="auhfmn4jd"/><path class="xsr2o7bxe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:laptop4-duotone" {...props}></Icon>

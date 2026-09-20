<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kdpl1_b6g.css';
import '../../css/t/tnz6rr6tu.css';
import '../../css/m/m9c-xccpi.css';
import '../../css/v/v81qvsl_p.css';
import '../../css/s/ssza2qbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kdpl1_b6g"/><path clip-rule="evenodd" class="tnz6rr6tu"/><path class="m9c-xccpi"/><path clip-rule="evenodd" class="v81qvsl_p"/><path class="ssza2qbav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:radio-duotone" {...props}></Icon>

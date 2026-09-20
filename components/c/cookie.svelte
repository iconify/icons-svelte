<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/layk_1_0b.css';
import '../../css/e/eeie_9rnp.css';
import '../../css/b/b8jl9_b7q.css';
import '../../css/n/n-g-eab-h.css';
import '../../css/b/b-j9xvyww.css';
import '../../css/c/c-wcjh2dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="layk_1_0b"/><circle class="eeie_9rnp"/><circle class="b8jl9_b7q"/><circle class="n-g-eab-h"/><circle class="b-j9xvyww"/><circle class="c-wcjh2dv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cookie" {...props}></Icon>

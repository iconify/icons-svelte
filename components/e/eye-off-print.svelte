<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dru9-5oma.css';
import '../../css/f/fr5kl9bxl.css';
import '../../css/p/pinqdebty.css';
import '../../css/b/b6i3s7bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dru9-5oma"/><path clip-rule="evenodd" class="fr5kl9bxl"/><path class="pinqdebty"/><path class="b6i3s7bvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:eye-off-print" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lu1ywdb1f.css';
import '../../css/b/bucfw6bdg.css';
import '../../css/q/qy44fxbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lu1ywdb1f"/><path class="bucfw6bdg"/><path class="qy44fxbnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-calling-rounded-line-duotone" {...props}></Icon>

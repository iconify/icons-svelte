<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k44r3ubuy.css';
import '../../css/e/elbw__bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k44r3ubuy"/><path clip-rule="evenodd" class="elbw__bus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:flash-timer-flat" {...props}></Icon>

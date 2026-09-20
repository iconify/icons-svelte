<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2u665ban.css';
import '../../css/p/p8maj_bay.css';
import '../../css/l/lque48_fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path class="p8maj_bay"/><path class="lque48_fa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:dashboard-gauge-2" {...props}></Icon>

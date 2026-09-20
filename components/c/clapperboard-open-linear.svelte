<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l6fn0fb1j.css';
import '../../css/h/htd9n0b_o.css';
import '../../css/q/qgxak08we.css';
import '../../css/e/ezgo-k8an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l6fn0fb1j"/><path class="htd9n0b_o"/><path class="qgxak08we"/><path class="ezgo-k8an"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clapperboard-open-linear" {...props}></Icon>

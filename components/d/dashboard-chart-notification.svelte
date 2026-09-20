<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/lm2y_hbzh.css';
import '../../css/k/kiph3vb6t.css';
import '../../css/x/x40pc3c5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="lm2y_hbzh"/><path class="kiph3vb6t"/><path class="x40pc3c5r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-chart-notification" {...props}></Icon>

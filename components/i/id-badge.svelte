<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x3k-zm7mc.css';
import '../../css/k/kg9gciblh.css';
import '../../css/r/rgjqzacvp.css';
import '../../css/q/que8_rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="x3k-zm7mc"/><path class="kg9gciblh"/><circle class="rgjqzacvp"/><path class="que8_rbvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:id-badge" {...props}></Icon>

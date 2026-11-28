<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dp12a2bii.css';
import '../../css/r/rhre_2l0s.css';
import '../../css/m/mp65rxbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="dp12a2bii"/><path class="rhre_2l0s"/><path class="mp65rxbup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-quote" {...props}></Icon>

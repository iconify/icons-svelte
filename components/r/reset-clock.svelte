<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xlag7ibmb.css';
import '../../css/t/t31jrybwu.css';
import '../../css/n/njow6lhet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xlag7ibmb"/><path class="t31jrybwu"/><path class="njow6lhet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:reset-clock" {...props}></Icon>

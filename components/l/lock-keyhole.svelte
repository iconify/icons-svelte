<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m39im5btg.css';
import '../../css/i/irx-iw8lh.css';
import '../../css/u/u2ffjhxgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="m39im5btg"/><path class="irx-iw8lh"/><circle class="u2ffjhxgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:lock-keyhole" {...props}></Icon>

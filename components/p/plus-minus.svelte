<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m_n3hfvmo.css';
import '../../css/v/vx6s_6z_m.css';
import '../../css/l/l9asld1on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="m_n3hfvmo"/><path class="vx6s_6z_m"/><path class="l9asld1on"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:plus-minus" {...props}></Icon>

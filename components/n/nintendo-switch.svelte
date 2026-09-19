<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xuuig3bfw.css';
import '../../css/m/mjv0wacus.css';
import '../../css/q/qlniz9tvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xuuig3bfw"/><path class="mjv0wacus"/><path class="qlniz9tvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:nintendo-switch" {...props}></Icon>

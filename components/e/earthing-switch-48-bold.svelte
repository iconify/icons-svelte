<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1zbnl2gi.css';
import '../../css/u/u_65e3bqj.css';
import '../../css/l/ld-zmgngl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c1zbnl2gi"/><path class="u_65e3bqj"/><path class="ld-zmgngl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:earthing-switch-48-bold" {...props}></Icon>

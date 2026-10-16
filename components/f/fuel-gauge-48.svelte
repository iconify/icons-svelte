<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlusl2c1l.css';
import '../../css/v/v1u1ysozk.css';
import '../../css/j/jwidh_pae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dlusl2c1l"/><path class="v1u1ysozk"/><path class="jwidh_pae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-gauge-48" {...props}></Icon>

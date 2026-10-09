<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw5w10zib.css';
import '../../css/s/s5u-maceu.css';
import '../../css/q/qkc80i2jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yw5w10zib"/><path class="s5u-maceu"/><path class="qkc80i2jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydro-turbine-48" {...props}></Icon>

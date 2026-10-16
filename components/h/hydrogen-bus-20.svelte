<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mneset-vt.css';
import '../../css/i/iha57zbze.css';
import '../../css/x/xrneb2bxe.css';
import '../../css/j/j2xr3seuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mneset-vt"/><path class="iha57zbze"/><path class="xrneb2bxe"/><path class="j2xr3seuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-bus-20" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he0-9w7up.css';
import '../../css/g/gsa3x5b0c.css';
import '../../css/p/p2d0_rjcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="he0-9w7up"/><path class="gsa3x5b0c"/><path class="p2d0_rjcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hybrid-inverter-48-bold" {...props}></Icon>

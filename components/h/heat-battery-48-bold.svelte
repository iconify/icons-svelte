<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxmtgk7_c.css';
import '../../css/e/el25l0wwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uxmtgk7_c"/><path class="el25l0wwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-battery-48-bold" {...props}></Icon>

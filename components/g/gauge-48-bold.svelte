<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_q60hbmc.css';
import '../../css/v/vlw_01baz.css';
import '../../css/g/gxf5i4yhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i_q60hbmc"/><path class="vlw_01baz"/><path class="gxf5i4yhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gauge-48-bold" {...props}></Icon>

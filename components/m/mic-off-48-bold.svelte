<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isr_8i8ag.css';
import '../../css/t/tp3yspbee.css';
import '../../css/p/phox42bnd.css';
import '../../css/p/p23qiccjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="isr_8i8ag"/><path class="tp3yspbee"/><path class="phox42bnd"/><path class="p23qiccjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mic-off-48-bold" {...props}></Icon>

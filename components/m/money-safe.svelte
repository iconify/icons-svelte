<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/x5t60kbnz.css';
import '../../css/i/ifwka7jyb.css';
import '../../css/t/tti1bth-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="x5t60kbnz"/><path class="ifwka7jyb"/><path class="tti1bth-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:money-safe" {...props}></Icon>

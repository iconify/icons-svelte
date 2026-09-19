<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l546r6byy.css';
import '../../css/d/dqrzf1bnz.css';
import '../../css/a/avr8ui1vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="l546r6byy"/><path class="dqrzf1bnz"/><path class="avr8ui1vm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:plus-print" {...props}></Icon>

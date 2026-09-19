<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qkjly7bav.css';
import '../../css/d/ds3epib7h.css';
import '../../css/i/imc13j2-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qkjly7bav"/><path class="ds3epib7h"/><path class="imc13j2-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:noodles" {...props}></Icon>

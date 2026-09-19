<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/x/xxysssc4x.css';
import '../../css/x/x1mme-tue.css';
import '../../css/m/mj1my2lvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="xxysssc4x"/><path class="x1mme-tue"/><path class="mj1my2lvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:flask" {...props}></Icon>

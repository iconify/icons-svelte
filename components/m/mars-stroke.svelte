<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e1t_zcbec.css';
import '../../css/q/qe8f45-ff.css';
import '../../css/z/z8dp_68if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e1t_zcbec"/><path class="qe8f45-ff"/><path class="z8dp_68if"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mars-stroke" {...props}></Icon>

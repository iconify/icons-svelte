<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qrgc488qh.css';
import '../../css/m/mmlua4bng.css';
import '../../css/v/v2ukonb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qrgc488qh"/><path class="mmlua4bng wm-a"/><path class="v2ukonb-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:map-pin-check-duo" {...props}></Icon>

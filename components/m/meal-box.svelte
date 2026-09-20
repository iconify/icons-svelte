<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/k/kcxthib1x.css';
import '../../css/j/jro3hvb0k.css';
import '../../css/l/lyew2g4yv.css';
import '../../css/p/p55ze_r2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="kcxthib1x"/><path class="jro3hvb0k"/><rect class="lyew2g4yv"/><rect class="p55ze_r2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:meal-box" {...props}></Icon>

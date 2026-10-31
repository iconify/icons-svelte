<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g4a0tubzg.css';
import '../../css/q/q7l5kgbhg.css';
import '../../css/c/c2_2vuu0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g4a0tubzg wm-k"/><path class="q7l5kgbhg wm-shine"/><path class="c2_2vuu0f wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:avatar-frog" {...props}></Icon>

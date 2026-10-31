<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fwx-c_0pd.css';
import '../../css/f/fyahubr1s.css';
import '../../css/r/rt9v9sb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fwx-c_0pd wm-k"/><path class="fyahubr1s wm-shine"/><path class="rt9v9sb0t wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:folder-lock" {...props}></Icon>

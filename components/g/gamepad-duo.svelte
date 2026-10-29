<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/ok4_19xwb.css';
import '../../css/t/tcjvbpb5r.css';
import '../../css/l/lo-bdo53p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ok4_19xwb"/><path class="tcjvbpb5r wm-a"/><path class="lo-bdo53p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gamepad-duo" {...props}></Icon>

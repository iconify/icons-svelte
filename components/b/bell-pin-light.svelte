<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t8pej6b5h.css';
import '../../css/h/hzsbvcczg.css';
import '../../css/l/le0nq6m2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="t8pej6b5h"/><path class="hzsbvcczg"/><circle class="le0nq6m2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:bell-pin-light" {...props}></Icon>

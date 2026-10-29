<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hmb0o_-2y.css';
import '../../css/b/b86buo32x.css';
import '../../css/d/dyvgatb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hmb0o_-2y wm-a"/><path class="b86buo32x"/><path class="dyvgatb7a wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lock-keyhole" {...props}></Icon>

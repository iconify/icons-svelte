<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/ey1zp4b_a.css';
import '../../css/b/b0q5uxwll.css';
import '../../css/g/gorsochjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ey1zp4b_a"/><path class="b0q5uxwll wm-a"/><path class="gorsochjg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-pull-request-draft-duo" {...props}></Icon>

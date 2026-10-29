<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/ey1zp4b_a.css';
import '../../css/g/gorsochjg.css';
import '../../css/q/qy6s686ad.css';
import '../../css/y/yatyg0v9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ey1zp4b_a"/><path class="gorsochjg"/><path class="qy6s686ad"/><path class="yatyg0v9y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-pull-request-duo" {...props}></Icon>

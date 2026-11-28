<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d12-a_mpa.css';
import '../../css/q/qrfll9i5r.css';
import '../../css/g/gi1w600zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d12-a_mpa"/><path class="qrfll9i5r"/><path class="gi1w600zg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:reply-all" {...props}></Icon>

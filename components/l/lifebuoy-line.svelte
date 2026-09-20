<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf2faab1e.css';
import '../../css/h/hevx8wb2o.css';
import '../../css/o/osvywl-4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf2faab1e"/><path class="hevx8wb2o"/><path class="osvywl-4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lifebuoy-line" {...props}></Icon>

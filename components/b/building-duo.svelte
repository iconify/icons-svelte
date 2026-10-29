<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uhidrxbyb.css';
import '../../css/r/r309anzoi.css';
import '../../css/e/euhc06b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="uhidrxbyb"/><path class="r309anzoi wm-a"/><path class="euhc06b6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:building-duo" {...props}></Icon>

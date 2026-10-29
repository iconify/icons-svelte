<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pl7qk7bwz.css';
import '../../css/a/a0-g48brp.css';
import '../../css/q/q19uih-go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pl7qk7bwz"/><path class="a0-g48brp wm-a"/><path class="q19uih-go"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pen-line-duo" {...props}></Icon>

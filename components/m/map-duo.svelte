<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b7kyjwrad.css';
import '../../css/p/p2z9olxff.css';
import '../../css/e/eoiz0rolg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b7kyjwrad"/><path class="p2z9olxff wm-a"/><path class="eoiz0rolg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:map-duo" {...props}></Icon>

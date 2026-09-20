<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfm4-3b6w.css';
import '../../css/e/es9h9dxow.css';
import '../../css/b/b8w7fnbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfm4-3b6w"/><path class="es9h9dxow"/><path class="b8w7fnbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:dashboard-browser-gauge" {...props}></Icon>

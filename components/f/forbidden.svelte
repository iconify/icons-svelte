<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/f/f8mualbjk.css';
import '../../css/z/z2gyqt3jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="f8mualbjk"/><path class="z2gyqt3jv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:forbidden" {...props}></Icon>

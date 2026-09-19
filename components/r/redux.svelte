<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy-61duhk.css';
import '../../css/m/modq6pbhs.css';
import '../../css/l/lixkakb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="uy-61duhk"/><path class="modq6pbhs"/><path class="lixkakb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:redux" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-jo3d9_a.css';
import '../../css/f/f7bx2zbyl.css';
import '../../css/w/wlr77q6kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-jo3d9_a"/><path class="f7bx2zbyl"/><path class="wlr77q6kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-layer" {...props}></Icon>

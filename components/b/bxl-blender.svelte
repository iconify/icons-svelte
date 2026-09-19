<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvqpbpbpk.css';
import '../../css/g/gpfbyab6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvqpbpbpk"/><path class="gpfbyab6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-blender" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj2h69bvg.css';
import '../../css/x/x0l9201mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj2h69bvg"/><path class="x0l9201mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-webcam" {...props}></Icon>

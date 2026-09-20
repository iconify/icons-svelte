<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffx328bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ffx328bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:die-face-with-three-pips" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reb0h0_rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="reb0h0_rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:note" {...props}></Icon>

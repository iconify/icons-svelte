<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj_h99bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fj_h99bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:landmark-jp" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e66cusbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="e66cusbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:image-flash-1-flash-power-connect-charge-electricity-lightning" {...props}></Icon>

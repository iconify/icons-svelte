<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1njp3l4b.css';
import '../../css/e/eymp5g2ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v1njp3l4b"/><path class="eymp5g2ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:moon-last-quarter" {...props}></Icon>

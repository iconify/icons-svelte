<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnzfpab_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnzfpab_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:husqvarna" {...props}></Icon>

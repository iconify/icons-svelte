<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2od65-nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="v2od65-nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:airport-11" {...props}></Icon>

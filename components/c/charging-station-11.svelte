<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-xppwbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="g-xppwbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:charging-station-11" {...props}></Icon>

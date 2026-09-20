<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9yvzfgbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="r9yvzfgbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:hospital-11" {...props}></Icon>

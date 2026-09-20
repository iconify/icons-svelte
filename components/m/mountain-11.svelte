<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx7nh0b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="tx7nh0b0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:mountain-11" {...props}></Icon>

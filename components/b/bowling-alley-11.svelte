<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6c1n8bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="q6c1n8bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bowling-alley-11" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw_v8cb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xw_v8cb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:ktor" {...props}></Icon>

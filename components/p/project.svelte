<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz3ebhbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lz3ebhbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:project" {...props}></Icon>

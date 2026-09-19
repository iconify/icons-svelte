<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6yvhc_zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a6yvhc_zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-coverage" {...props}></Icon>

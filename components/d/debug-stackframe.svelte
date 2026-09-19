<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-m0grb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h-m0grb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-stackframe" {...props}></Icon>

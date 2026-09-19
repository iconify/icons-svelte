<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mshchebaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mshchebaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-step-over" {...props}></Icon>

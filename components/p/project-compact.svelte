<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-g7-bxba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="i-g7-bxba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:project-compact" {...props}></Icon>

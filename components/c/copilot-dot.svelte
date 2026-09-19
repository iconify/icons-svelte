<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_k0mzjpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x_k0mzjpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:copilot-dot" {...props}></Icon>
